# [87. Building Blocks](https://cssbattle.dev/play/87)

![](https://cssbattle.dev/targets/87.png)

```HTML
<div class="rectangle one"></div>
<div class="center"></div>
<div class="rectangle two"></div>
<style>
  body {
    background-color: #F3AC3C;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .rectangle {
    width: 150px;
    height: 100px;
    background: #1A4341;
    border-radius: 10px
  }
  .one {
    translate: 15px -35px
  }
  .two {
    translate: -15px 35px;
  }
  .center {
    position: absolute;
    height: 70px;
    width: 70px;
    background-color: #F3AC3C;
    border-radius: 10px;
    z-index: 3;
  }
</style>
```
