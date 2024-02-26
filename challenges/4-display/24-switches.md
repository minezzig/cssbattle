# [24. Switches](https://cssbattle.dev/play/24)

![](https://cssbattle.dev/targets/24.png)

```HTML
<div class="left-switch"></div>
<div class="right-switch"></div>
<div class="toggle1"></div>
<div class="toggle2"></div>
<style>
  body {
    background: #62306D;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .left-switch {
    background: #AA445F;
    height: 150;
    width: 100px;
    border-radius: 50px;
    position: absolute;
    left: 80px;
    top: 50px;
  }

  .right-switch {
    background: #E38F66;
    height: 150;
    width: 100px;
    border-radius: 50px;
    position: absolute;
    right: 80px;
    bottom: 50px;
  }

  .toggle1 {
    background: #F7EC7D;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    z-index: 2;
    position: absolute;
    left: 80px;
  }

  .toggle2 {
    background: #F7EC7D;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    z-index: 2;
    position: absolute;
    right: 80px;
  }
</style>
```
