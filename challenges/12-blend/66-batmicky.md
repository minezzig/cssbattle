# [66. Batmicky](https://cssbattle.dev/play/66)

![](https://cssbattle.dev/targets/66.png)

```HTML
<div class="body"></div>
<div class="head-space"></div>
<div class="head"></div>
<div class="ears one"></div>
<div class="ears two"></div>
<div class="cutout-one"></div>
<div class="cutout-two"></div>
<div class="cutout-three"></div>
<div class="cutout-four"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .body {
    background: #F2AD43;
    width: 230px;
    height: 80px;
    position: absolute;
    top: 100px;
  }
  
  .head-space {
    background: #191919;
    border-radius: 10px;
    width: 80px;
    height: 50px;
    position: absolute;
    top: 80px;
  }
  
  .head {
    background: #F2AD43;
    width: 20px;
    height: 20px;
    position: absolute;
    top: 110px;
  }
  
  .ears {
    background: #F2AD43;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    position: absolute;
  }
  
  .one {
    top: 105px;
    left: 185px;
  }
  
  .two {
    top: 105px;
    right: 185px;
  }
  
  .cutout-one {
    background: #191919;
    border-radius: 50%; ;
    height: 100px;
    width: 100px;
    position: absolute;
    top: 100px;
    left: 25px;
  }
  
  .cutout-two {
    background: #191919;
    border-radius: 50%;
    height: 100px;
    width: 140px;
    position: absolute;
    top: 160px;
    left: 75px;
  }

  .cutout-three {
    background: #191919;
    border-radius: 50%;
    height: 100px;
    width: 140px;
    position: absolute;
    top: 160px;
    right: 75px;
  }
  
  .cutout-four {
    background: #191919;
    border-radius: 50px; ;
    height: 100px;
    width: 100px;
    position: absolute;
    top: 100px;
    right: 25px;
  }
</style>

```
