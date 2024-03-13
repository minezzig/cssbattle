# [111. Rain Drops](https://cssbattle.dev/play/111)

![](https://cssbattle.dev/targets/111.png)

```HTML
<div class="top"></div>
<div class="left"></div>
<div class="bottom"></div>
<style>
  body {
    background-color: #F3AC3C;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    width: 80px;
    height: 80px;
    background: #254241;
    border-radius: 50%;
    position: absolute;
        border-bottom-right-radius: 0%;

  }
  .top {
    top: 40px;
    rotate: 45deg;
  }
  .left {
    rotate: -45deg;
    left: 80px;
  }
  .bottom {
    rotate: -135deg;
    bottom: 40px
  }
</style>
```
