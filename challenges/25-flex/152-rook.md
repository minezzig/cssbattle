# [152. Rook](https://cssbattle.dev/play/152)

![](https://cssbattle.dev/targets/152.png)

```HTML
<div class="top"></div>
<div class="container">
  <div class="middle"></div>
</div>
<div class="base"></div>
<style>
  body {
    background: #62306D;
    height: 100%;
    margin: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .top {
    width: 90px;
    height: 20px;
    background: #F7EC7D;
    border-radius: 0 0 10px 10px;
    position: relative;
    top: 95px;
  }
  .top::after {
    content: "";
    position: absolute;
    height: 50px;
    width: 10px;
    background: #F7EC7D;
    border-radius: 50px;
    bottom: 10px;
    box-shadow: 40px 0 0 #F7EC7D, 80px 0 0 #F7EC7D;
  }
  .top::before {
    content: "";
    position: absolute;
    height: 20px;
    width: 30px;
    background: #62306D;
    border-radius: 0 0 5px 5px;
    translate: 10px -15px;
    box-shadow: 40px 0  0 #62306D;
  }
  .container {
    padding: 0;
    margin: 5;
    position: absolute;
    bottom: 95px;
  }
  .container::before{
    content: "";
    height: 90px;
    width: 50px;
    background: #62306D;
    position: absolute;
    border-radius: 50%;
    left: -23px;
    bottom: -5;
    rotate: 17deg;
  }
  .container::after{
    content: "";
    height: 90px;
    width: 50px;
    background: #62306D;
    position: absolute;
    border-radius: 50%;
    right: -23px;
    bottom: -5;
    rotate: -17deg;
    z-index: 0;
  }
  .middle {
    background: #F7EC7D;
    height: 65px;
    width: 100px;
  }
  .middle::before {
    content: "";
    position: absolute;
    width: 60px;
    height: 10px;
    background: #F7EC7D;
    top: -15px;
    border-radius: 50px;
    left: 20px;
    z-index: 100;
  }
  .middle::after {
    content: "";
    position: absolute;
    width: 110px;
    height: 10px;
    background: #F7EC7D;
    bottom: -15px;
    border-radius: 50px;
    left: -5px
  }

  .base {
    width: 140px;
    height: 25px;
    background: #F7EC7D;
    border-radius: 50px 50px 20px 20px;
    position: absolute;
    bottom: 55px;
  }
</style>

```
