# [106. Ryuk's Apple](https://cssbattle.dev/play/106)

![](https://cssbattle.dev/targets/106.png)

```HTML
<div class="bite"></div>
<div class="apple right"></div>
<div class="apple left"></div>
<div class="stem"></div>
<style>
  body {
    background: #000000;
    margin: 0;
  }
  .bite {
    background: #000000;
    height: 55px;
    width: 55px;
    border-radius: 50%;
    position: absolute;
    top: 100px;
    left: 95px;
    z-index: 23;
    box-shadow: 0 40px 
  }
  .apple {
    width: 100px;
    height: 120px;
    background: #D4392D;
    position: absolute;
    border-radius: 50%;
    top: 90px;
  }
  .right {
    right: 120px;
    rotate: 30deg;
  }
  .left {
    content: "";
    left: 120px;
    rotate: -30deg;
  }
  .stem {
    background: #D4392D;
    width: 10px;
    height: 80px;
    position: absolute;
    top: 70px;
    left: 195px
  }
</style>

```
