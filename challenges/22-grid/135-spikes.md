# [135. Spikes](https://cssbattle.dev/play/135)

![](https://cssbattle.dev/targets/135.png)

```HTML
<div class="container">
<div class="triangle-left"></div>
  <div class="triangle-right"></div>
<div class="top left"></div>
<div class="bottom left"></div>
<div class="top right"></div>
<div class="bottom right"></div>

</div>
<style>
  body {
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #E3516E;
  }
  .container {
    width: 160px;
    height: 100px;
    position: relative;
  }
  .top {
    background-color: #D9D9D9;
    width: 70px;
    height: 40px;
    border-radius: 0 50px 50px 0;
    position: absolute
  }
  .bottom {
    background-color: #D9D9D9;
    width: 70px;
    height: 40px;
    border-radius: 0 50px 50px 0;
    position: absolute;
    bottom: 0;
  }
  .left {
    border-radius: 50px 0 0 50px;
    right: 0;
  }
  .triangle-left {
    background-color: transparent;
    height: 0;
    border-top: 50px solid transparent;
    border-bottom: 50px solid transparent;
    border-left: 50px solid #E3516E;
    position: absolute;
    z-index: 2;
  }
  .triangle-right {
    background-color: transparent;
    height: 0;
    border-top: 50px solid transparent;
    border-bottom: 50px solid transparent;
    border-right: 50px solid #E3516E;
    position: absolute;
    right: 0;
    z-index: 2;
  }
</style>
```
