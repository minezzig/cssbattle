# [110. Sunrays](https://cssbattle.dev/play/110)

![](https://cssbattle.dev/targets/110.png)

```HTML
<div class="d1"></div>
<div class="d2"></div>
<div class="d3"></div>
<div class="d4"></div>
<div class="d5"></div>
<div class="d6"></div>
<div class="d7"></div>
<style>
  body {
    background-color: #D25B70;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    width: 10px;
    height: 100px;
    border-radius: 5px;
    background: #F2E09F;
    position: absolute;
    translate: 0 -20px
  }
  .d1 {
     
  }
  .d2 {
    top: 110px;
    right: 160px;
    rotate: 30deg
  }
  .d3 {
    top: 110px;
    left: 160px;
    rotate: -30deg;
  }
  .d4 {
    rotate: -60deg;
    bottom: 65px;
    left: 135px
  }
  .d5 {
    rotate: 60deg;
    bottom: 65px;
    right: 135px
  }
  .d6 {
    rotate: 90deg;
    bottom: 30px;
    left: 125px
  }
  .d7 {
    rotate: 90deg;
    bottom: 30px;
    right: 125px
  }
</style>


```
