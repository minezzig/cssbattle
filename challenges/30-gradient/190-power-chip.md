# [190. Power Chip](https://cssbattle.dev/play/190)

![](https://cssbattle.dev/targets/190.png)

```HTML
<div class="panel">
  <div class="arrow"></div>
</div>
<div class="indent"></div>
<div class="panel">
  <div class="arrow"></div>
</div>
<style>
  body {
    background-color: #E3516E;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .arrow {
    background-color: #E3516E;
    height: 90px;
    width: 50px;
    position: absolute;
    left: 50%;
    bottom: 0;
    translate: -50%;
    clip-path: polygon(0 40px, 50% 0, 100% 40px, 35px 40px, 35px 100%, 15px 100%, 15px 40px, 0 40px)
  }
  .panel {
    width: 130px;
    height: 150px;
    background: #FADE8B;
    margin: 10px;
    position: relative;
  }
  .indent {
    z-index: 10;
    height: 85px;
    width: 105px;
    position: absolute;
    background-color: #E3516E;
    clip-path: polygon(0 0,  100% 0, 50% 100%, 0 0);
    top: 75px;
  }
</style>

```
