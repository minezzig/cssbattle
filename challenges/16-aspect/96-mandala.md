# [96. Mandala](https://cssbattle.dev/play/96)

![](https://cssbattle.dev/targets/96.png)

```HTML
<div class="circle"></div>
<div class="top"></div>
<div class="bottom"></div>
<div class="left"></div>
<div class="right"></div>
<style>
  body {
    background-color: #243D83;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .circle {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: #6592CF;
    position: relative;
  }
  .top {
      position: absolute;
        width: 125px;
    height: 125px;
    border-radius: 50%;
    border: 20px solid #243D83;
    background: transparent;
    bottom: 47%;
  }
    .bottom {
      position: absolute;
        width: 125px;
    height: 125px;
    border-radius: 50%;
    border: 20px solid #243D83;
    background: transparent;
    top: 47%;
  }
      .left {
      position: absolute;
        width: 125px;
    height: 125px;
    border-radius: 50%;
    border: 20px solid #243D83;
    background: transparent;
    right: 47%;
  }
      .right {
      position: absolute;
        width: 125px;
    height: 125px;
    border-radius: 50%;
    border: 20px solid #243D83;
    background: transparent;
    left: 47%;
  }
</style>
```
