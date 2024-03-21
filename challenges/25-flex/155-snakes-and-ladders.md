# [155. Snakes & Ladders](https://cssbattle.dev/play/155)

![](https://cssbattle.dev/targets/155.png)

```HTML
<div class="ladder left"></div>
<div class="ladder right"></div>
<div class="rung"></div>

<style>
  body {
    background: #6592CF;
    box-sizing: border-box;
    margin: 0;
  }
  .ladder {
    width: 30px;
    height: 240px;
    position: absolute;
    bottom: 0;
    background: #060F55;
    border-radius: 15px 15px 0 0;
  }
  .left {
    left: 120px;
  }
  .right {
    right: 120px;
  }
  .rung, ::before, ::after {
    background: #060F55;
    height: 30px;
    width: 120px;
    position: absolute;
    left: 140px;
    top: 180px;
  }
  .rung::before {
    content: "";
    top: -60px;
    left: 0;
  }
    .rung::after {
    content: "";
    top: 60px;
    left: 0;
  }
</style>

```
