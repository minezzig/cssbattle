# [125. Root Learn](https://cssbattle.dev/play/125)

![](https://cssbattle.dev/targets/125.png)

```HTML
<div class="top"></div>
<div class="leg"></div>
<div class="foot one"></div>
<div class="foot two"></div>
<div class="foot three"></div>
<div class="rightFoot"></div>

<style>
  body {
    background: #EFF2F1;
    margin: 0;
    box-sizing: border-box;
  }
  .top, .top::after {
    position: absolute;
   
  }
  .top {
    background: #1C1C1C;
    border-radius: 0 45px 45px 0;
    width: 130px;
    height: 90px;
    top: 60px;
    left: 130px;
  }
  .top::after {
    content: "";
    width: 50px;
    height: 60px;
    top: 15px;
    background: #EFF2F1;
    left: 40px;
    border-radius: 0 50px 50px 0;
  }
  .leg, .leg::after {
    background: #1C1C1C;
    width: 40px;
    height: 100px;
    position: absolute;
  }
  .leg {
       bottom: 60px;
    left: 130px;
  }
  .leg::after {
    content: "";
    width: 46px;
    left: 102px;
    transform-origin: bottom left;
    transform: skew(30deg);
  }
  .foot {
    background: #1C1C1C;
    height: 25px;
    width: 25px;
    position: absolute;
    clip-path: polygon(0px 16px, 25px 0px, 25px 25px, 0px 25px)  
  }
  .one {
    top: 60px;
    left: 110px;
    transform: rotateX(180deg);
  }
  .two {
    bottom: 60px;
    left: 165px;
    transform: rotateY(180deg);
  }
  .three {
    bottom: 60px;
    left: 110px;
  }
  .rightFoot {
    background: #1C1C1C;
    height: 25px;
    width: 30px;
    position: absolute;
    clip-path: polygon(0px 1px, 30px 20px, 30px 25px, 0 25px);
    right: 110px;
    bottom: 60px
  }
</style>
```
