# [117. Arineo](https://cssbattle.dev/play/117)

![](https://cssbattle.dev/targets/117.png)

```HTML
<div class="a left"></div>
<div class="a right"></div>
<div class="ball"></div>
<div class="container">
  <div class="check"></div>
</div>
<style>
  body {
    background-color: #FFFFFF;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .a {
    background-color: #2E2926;
    height: 180px;
    width: 45px;
    transform-origin: top;
  }
  .left {
    transform: skew(25deg);
    translate: 24px;
  }
  .right {
     transform: skew(-25deg);
    translate: -24px;
  }
  .ball {
    background: #0088CA;
    height: 22px;
    width: 22px;
    border-radius: 50%;
    position: absolute;
  }
  .check {
    width: 160px;
    height: 200px;
    rotate: -45deg;
    background: transparent;
    border: 8px solid white;
    box-shadow:  0 0 0 20px #0088CA,
                 0 0 0 28px #FFFFFF;
    position: relative;
    bottom: 130px;
    left: -23px;
  }
  .container {
    position: absolute;
    overflow: hidden;

    width: 200px;
    height: 145px;
    bottom: 80px;
    left: 120px;
  }
</style>


```
