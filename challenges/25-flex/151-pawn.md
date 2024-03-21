# [151. Pawn](https://cssbattle.dev/play/151)

![](https://cssbattle.dev/targets/151.png)

```HTML
<div class="top"></div>
<div class="ridge"></div>
<div class="middle"></div>
<div class="base"></div>


<style>
  body {
    background: #F5D6B4;
    margin: 0;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100%;
    gap: 5px
  }
  .top {
    width: 50px;
    aspect-ratio: 1;
    background: #dd6b4d;
    border-radius: 50%;
    z-index: 4;
  }
  .ridge {
    background: #D86F45;
    width: 80px;
    height: 20px;
    border-radius: 10px 10px 30px 30px;
    z-index: 5;

  }
  .middle {
    background: #D86F45;
    width: 80px;
    height: 65px;
    position: relative;
  }
  .middle::before, .middle::after {
    content: "";
    position: absolute;
    background: #F5D6B4;
    height: 100px;
    width: 52px;
    border-radius: 50%;
  }
  .middle::before {
    left: -34px;
    rotate: 10deg;
    bottom: -5px;
  }
  .middle::after {
    right: -34px;
    rotate: -10deg;
    bottom: -5px;

  }
  .base {
    background: #D86F45;
    width: 140px;
    height: 40px;
    border-radius: 20px 20px 10px 10px;
    z-index: 5;
  }
</style>
```
