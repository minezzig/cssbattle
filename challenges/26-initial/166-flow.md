# [166. Flow](https://cssbattle.dev/play/166)

![](https://cssbattle.dev/targets/166.png)

```HTML
<div class="top"></div>
<div class="bottom"></div>
<style>
  body {
    background: #D86F45;
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .top {
    width: 80px;
    height: 100px;
    background: #FDFBF8;
    border-radius: 0 0 50px 50px;
    position: relative;
  }
  .top::before, .top::after {
    content: "";
    position: absolute;
    width: 30px;
    height: 125px;
    background: #FDFBF8;
    border-radius: 0 0 20px 20px
  }
  .top::before {
    left: -60px;
  }
  .top::after {
    right: -60px;
  }
  .bottom {
    width: 200px;
    height: 100px;
    background: #FDFBF8;
    position: absolute;
    bottom: 30px;
    border-radius: 0 0 100px 100px;
  }
  .bottom::before {
    content: "";
    height: 30px;
    aspect-ratio: 1;
    background: white;
    position: absolute;
    border-radius: 50%;
    top: -15px;
    box-shadow: 30px 0 #D86F45,
                140px 0 #D86F45,
                170px 0 #FDFBF8;
  }
  .bottom::after {
    content: "";
    background:#FDFBF8;
    width: 80px;
    aspect-ratio: 1;
    position: absolute;
    border-radius: 50%;
    left: 60px;
    top: -40px;
  }
</style>
```
