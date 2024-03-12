# [104. Amegakure](https://cssbattle.dev/play/104)

![](https://cssbattle.dev/targets/104.png)

```HTML
<div class="container">
  <div class="inside">
    <div class="dot"></div>
    <div class="line1"></div>
    <div class="line2"></div>
    <div class="line3"></div>
    <div class="line4"></div>
    <div class="dot2"></div>
  </div>
</div>
<style>
  html {
    box-sizing: border-box;
  }
  body {
    background-color: #000000;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .container {
    width: 240px;
    height: 120px;
    background: #37385A;
    border-radius: 20px;
  }
  .inside {
    width: 200px;
    height: 80px;
    background: linear-gradient(108deg,
      #9897AE 0,
      #9897AE 80px,
      #C0C3DB 80px,
      #C0C3DB 130px,
      #9897AE 130px,
      #9897AE 200px
    );
    border-radius: 10px;
    margin: 20px;
    position: relative;
  }
  .dot, .dot:before, .dot:after, 
  .dot2, .dot2:before, .dot2:after {
    content: "";
    background-color: black;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
  }
  .dot {
    top: 35px;
    left: 15px;
  }
  .dot:before {
    top: -20px;
  }
  .dot:after {
    bottom: -20px;
  }
  .dot2 {
    top: 35px;
    left: 175px;
  }
  .dot2:before {
    top: -20px;
  }
  .dot2:after {
    bottom: -20px;
  }
  .line1 {
    background-color: black;
    height: 50px;
    width: 10px;
    border-radius: 10px;
    position: absolute;
    top: 15px;
    left: 65px;
  }
    .line2 {
    background-color: black;
    height: 50px;
    width: 10px;
    border-radius: 10px;
    position: absolute;
    top: 15px;
    left: 85px;
  }
    .line3 {
    background-color: black;
    height: 50px;
    width: 10px;
    border-radius: 10px;
    position: absolute;
    top: 15px;
    left: 105px;
  }
    .line4 {
    background-color: black;
    height: 50px;
    width: 10px;
    border-radius: 10px;
    position: absolute;
    top: 15px;
    left: 125px;
  }
</style>


```
