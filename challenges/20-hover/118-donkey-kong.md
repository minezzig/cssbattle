# [118. Donkey Kong](https://cssbattle.dev/play/118)

![](https://cssbattle.dev/targets/118.png)

```HTML
<div class="one bar"></div>
<div class="two bar"></div>
<div class="three bar"></div>
<div class="pillar left"></div>
<div class="pillar middle"></div>
<div class="pillar right"></div>
<style>
  body {
    background-color: #000000;
    margin: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    
  }
  .bar {
    width: 300px;
    height: 20px;
    border-radius: 50px;
    background: #AF067C;
      z-index: 2;
  }
  .one {
    translate: 0 90px
  }
.two {
    translate: 0 120px;
    rotate: -4deg;
  }
  .three {
    translate: 0 150px;
  }
  .pillar {
    background: #FFFFFF;
    width: 20px;
    position: absolute;
  }
  .left {
    height: 50px;
    left: 80px;
    top: 100px
  }
  .middle {
    height: 50px;
    top: 150px;
  }
  .right {
    height: 100px;
    right: 80px;
    top: 100px;
  }
</style>
```
