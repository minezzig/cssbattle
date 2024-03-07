# [82. Diamond Cut](https://cssbattle.dev/play/82)

![](https://cssbattle.dev/targets/82.png)

```HTML
<div class="square"></div>
<div class="center"></div>
<div class="cutout"></div>
<div class="cutouttwo"></div>
<style>
  body {
    background-color: #F3AC3C;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .square {
    position: relative;
    right: 2px;
    height: 100px;
    width: 100px;
    background-color: #F3AC3C;
    border: solid 30px #998235;
    transform: rotate(45deg)
  }
  
  .center {
    background-color: #1A4341;
    height: 30px;
    width: 30px;
    position: absolute;
    left: 182px;
    transform: rotate(45deg);
  }
  
  .cutout {
    background-color: #F3AC3C;
    height: 30px;
    width: 30px;
    z-index: 2;
    position: absolute;
    transform: rotate(45deg);
    top: 89px;
    left: 137px;
  }
    .cutouttwo {
    background-color: #F3AC3C;
    height: 30px;
    width: 30px;
    z-index: 2;
    position: absolute;
    transform: rotate(45deg);
    top: 89px;
    right: 141px;
  }
  
</style>


```
