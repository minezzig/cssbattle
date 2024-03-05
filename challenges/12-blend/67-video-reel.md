# [67. Video Reel](https://cssbattle.dev/play/67)

![](https://cssbattle.dev/targets/67.png)

```HTML
<div class="verticles"></div>
<div class="cube c-one"></div>
<div class="cube c-two"></div>
<div class="cube c-three"></div>
<div class="cube c-four"></div>
<div class="rectangle r-one"></div>
<div class="rectangle r-two"></div>
<div class="rectangle r-three"></div>
<div class="rectangle r-four"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .verticles {
    background: #5DBCF9;
    position: absolute;
    width: 10px;
    height: 300px;
  }
  
  .verticles:before {
    content: "";
    background: #5DBCF9;
    position: absolute;
    width: 10px;
    height: 300px;
    right: 150px;
  }
  
  .verticles:after {
    content: "";
    background: #5DBCF9;
    position: absolute;
    width: 10px;
    height: 300px;
    left: 150px;
  }
  
  .cube {
    background: #5DBCF9;
    position: absolute;
    height: 40px;
    width: 55px;  
  }
  
  .c-one {
    left: 0;
    top: 80px;
  }
  
  .c-two {
    left: 0;
    bottom: 30px;
  }
  
  .c-three {
    right: 0;
    top: 30px;
  }
  
  .c-four {
    right: 0;
    bottom: 80px;
  }
  
  .rectangle {
    background: #5DBCF9;
    position: absolute;
    height: 40px;
    width: 150px;  
  }
  
  .r-one {
    left: 50;
    top: 30px;
  }
  
  .r-two {
    left: 50;
    top: 180px;
  }
  
  .r-three {
    right: 50;
    top: 80px;
  }
  
  .r-four {
    right: 50;
    top: 230px;
  }
</style>

```
