# [115. Droplet](https://cssbattle.dev/play/115)

![](https://cssbattle.dev/targets/115.png)

```HTML
<div class="top"></div>
<div class="bottom"></div>
<div class="circle"></div>
<style>
  body {
    background: linear-gradient(to bottom, #C36271 0 50%, #F2E09F 50% 100% );
    margin: 0;
  }

  .circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: linear-gradient(to bottom, #C36271 50%, #F2E09F 50% 100%);
    position: absolute;
    top: 50%;
    left: 50%;
    translate: -50% -50%;
  }
  .top {
    background-color: #F2E09F;
    height: 50%;
    width: 380px;
    border-bottom-right-radius: 100px;
  }
  .bottom {
    background-color: #C36271;
    height: 50%;
    width: 380px;
    position: absolute;
    left: 20px;
    border-top-left-radius: 100px;
  }
</style>
```
