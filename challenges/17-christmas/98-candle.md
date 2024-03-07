# [98. Candle](https://cssbattle.dev/play/98)

![](https://cssbattle.dev/targets/98.png)

```HTML
<div class="flame"></div>
<div class="tip"></div>
<div class="candle"></div>
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #14313E;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .tip {
    height: 30px;
    width: 60px;
    background-color: #14313E;
    position: absolute;
    border-radius: 50%/50%;
    top: 100px;
    z-index: 1;
  }  
  .flame {
    background-color: #F3AC3C;
    height: 50px;
    width: 30px;
    position: absolute;
    top: 60px;
    right: 170px;
    border-radius: 50px 0;
    z-index: 2;
  }
  .candle {
    width: 80px;
    height: 130px;
    background: #BA3E46;
    transform: translateY(25px);
    border-radius: 50%/10%;
  }
  .candle:before {
    content: "";
    background-color: #F3695A;
    position: absolute;
    width: 80px;
    height: 30px;
    border-radius: 60px/20px;
  }
</style>
```
