# [59. Earth](https://cssbattle.dev/play/59)

![](https://cssbattle.dev/targets/59.png)

```HTML
<div class="globe"></div>
<div class="left"></div>
<div class="right"></div>
<div class="vertical"></div>
<div class="horizontal"></div>



<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .globe {
    background: #4F77FF;
    width: 150px;
    height: 150px;
    border-radius: 50%;
  }
  
  .vertical {
    background: #191919;
    height: 400px;
    width: 10px;
    position: absolute;
  }
  
  .horizontal {
    background: #191919;
    height: 10px;
    width: 400px;
    position: absolute;
  }
  
  .horizontal:before {
    content: "";
    background: #191919;
    height: 10px;
    width: 400px;
    position: absolute;
    top: 40px;
  }
  
    .horizontal:after {
    content: "";
    background: #191919;
    height: 10px;
    width: 400px;
    position: absolute;
    top: -40px;
  }
  
  .left {
    border: 10px solid #191919;
    height: 190px;
    width: 190px;
    border-radius: 50%;
    position: absolute;
    right: 35px;
  }
  
    .right {
    border: 10px solid #191919;
    height: 190px;
    width: 190px;
    border-radius: 50%;
    position: absolute;
    left: 35px;
  }
</style>


```
