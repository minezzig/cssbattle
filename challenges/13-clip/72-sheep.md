# [72. Sheep](https://cssbattle.dev/play/72)

![](https://cssbattle.dev/targets/72.png)

```HTML
<div class="sheep one"></div>
<div class="sheep two"></div>
<div class="sheep three"></div>
<div class="sheep four"></div>
<div class="sheep five"></div>
<div class="sheep six"></div>
<div class="sheep seven"></div>
<div class="sheep eight"></div>
<div class="blackout"></div>
<div class="face"></div>
<div class="eye-left"></div>
<div class="eye-right"></div>


<style>
  body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #243D83;
  }
  
  .sheep {
    background: #6592CF;
    height: 50px;
    width: 60px;
    border-radius: 50%;
    position: absolute;
  }
  .one {
    top: 65px;
  }
  .two {
    transform: rotate(-45deg);
    top: 85px;
    left: 130px;
  }
  .three {
    transform: rotate(-90deg);
    left: 110px;
  }
  .four {
    transform: rotate(45deg);
    bottom: 85px;
    left: 130
  }
  .five {
    bottom: 65px;
  }
  .six {
    transform: rotate(-45deg);
    bottom: 85px;
    right: 130
  }
  .seven {
    transform: rotate(90deg);
    right: 110;
  }
  .eight {
    transform: rotate(45deg);
    top: 85px;
    right: 130px;
  }
  .blackout {
    background: #6592CF;
    width: 100px;
    height: 56px;
    position: absolute;
    bottom: 110px;
    
  }
  .face {
    position: absolute;
    background: #243D83;
    height: 41px;
    position: absolute;
    bottom: 125px;
    width: 60px;
    z-index: 2;
    border-radius: 0 0 50px 50px;
  }
  .eye-left {
    background: #6592CF;
    z-index: 5;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    top: 130px;
    left: 185px;   
  }
  .eye-right {
    background: #6592CF;
    z-index: 5;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    top: 130px;
    right: 185px;   
  }
  
</style>
```
