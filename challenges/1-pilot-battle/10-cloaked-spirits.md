# [10. Cloaked Spirits](https://cssbattle.dev/play/10)

![](https://cssbattle.dev/targets/10.png)

```html
<div class="base-top">
  <div class="middle-circle-outer big-circles">
    <div class="middle-circle-inner little-circles"></div>
  </div>
</div>
<div class="base-bottom">
  <div class="left-circle-outer big-circles">
    <div class="left-circle-inner little-circles"></div>
  </div>
  <div class="right-circle-outer big-circles">
    <div class="right-circle-inner little-circles"></div>
  </div>
</div>

<style>
  body {
    background-color: #62306d;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .base-bottom {
    background-color: #f7ec7d;
    width: 300px;
    height: 100px;
    position: absolute;
    bottom: 0px;
  }

  .base-top {
    background-color: #f7ec7d;
    height: 100px;
    width: 100px;
  }

  .big-circles {
    border-radius: 50%;
    height: 100px;
    width: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .little-circles {
    border-radius: 50%;
    height: 60px;
    width: 60px;
  }

  .left-circle-outer {
    background-color: #aa445f;
    position: absolute;
    top: -50px;
  }

  .left-circle-inner {
    background-color: #e38f66;
  }

  .right-circle-outer {
    background-color: #aa445f;
    position: absolute;
    top: -50px;
    right: 0px;
  }

  .right-circle-inner {
    background-color: #e38f66;
  }

  .middle-circle-outer {
    background-color: #e38f66;
    position: absolute;
    top: 50px;
  }

  .middle-circle-inner {
    background-color: #aa445f;
  }
</style>
```
