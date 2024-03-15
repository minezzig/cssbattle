# [120. Tank](https://cssbattle.dev/play/120)

![](https://cssbattle.dev/targets/120.png)

```HTML
<div class="short left"></div>
<div class="short right"></div>
<div class="long bottom"></div>
<div class="long side"></div>
<div class="bullets"></div>
<div class="ship"></div>
<div class="bar"></div>

<style>
  .ship, .ship::before, .ship::after {
    background: #54C144;
    width: 40px;
    height: 10px;
    position: absolute;
  }
  .ship {
        bottom: 75px;
    left: 70px;
  }
  .ship::before {
    content: "";
    bottom: 15px;
    right: 10px;
  }
  .ship::after {
    content: "";
    bottom: -15px;
    right: 10px;
  }
  .bar {
    background: #54C144;
    height: 40px;
    width: 20px;
    position: absolute;
    bottom: 60px;
    left: 70px;
  }
  .bullets, .bullets::after {
    background: white;
    height: 10px;
    width: 10px;
    position: absolute;
  }
  .bullets {
    bottom: 75px;
    left: 120px;
  }

  .bullets::after {
    content: "";
    left: 20px;
  }
  body {
    background: #000000;
    margin: 0;
    border: 20px solid #54C144;
  }
  .short {
    width: 80px;
    height: 40px;
    background: #C74E4E;
    position: absolute;
  }
  .left {
    top: 60px;
    left: 60px;
  }
  .right {
    top: 60px;
    left: 180px;
  }

  .long {
    width: 200px;
    height: 40px;
    background: #C74E4E;
    position: absolute;
  }

  .bottom {
    bottom: 120px;
    left: 60px;
  }

  .side {
    width: 180px;
    rotate: 90deg;
    left: 230px;
    bottom: 130px;
  }
</style>
```
