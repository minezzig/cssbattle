# [32. Band-aid](https://cssbattle.dev/play/32)

![](https://cssbattle.dev/targets/32.png)

```HTML
<div class="top-left"></div>
<div class="top-right"></div>
<div class="bottom-left"></div>
<div class="bottom-right"></div>
<div class="middle"></div>
<style>
  body {
    background: #FFFFFF;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .middle {
    height: 50px;
    width: 50px;
    background: #FBE18C;
    transform: rotate(45deg)
  }

  .top-left {
    background: #F3AC3C;
    transform: rotate(-45deg);
    height: 75px;
    width: 50px;
    position: absolute;
    top: 68px;
    left: 131px;
  }

  .top-right {
    background: #A3A368;
    transform: rotate(45deg);
    height: 75px;
    width: 50px;
    position: absolute;
    top: 68px;
    right: 131px;
  }
  .bottom-right {
    background: #F3AC3C;
    transform: rotate(-45deg);
    height: 75px;
    width: 50px;
    position: absolute;
    bottom: 68px;
    right: 131px;
  }

  .bottom-left {
    background: #A3A368;
    transform: rotate(45deg);
    height: 75px;
    width: 50px;
    position: absolute;
    bottom: 68px;
    left: 131px;
  }
</style>


```
