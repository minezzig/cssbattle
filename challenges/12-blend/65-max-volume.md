# [65. Max Volume](https://cssbattle.dev/play/65)

![](https://cssbattle.dev/targets/65.png)

```HTML
<div class="circle one"></div>
<div class="circle two"></div>
<div class="circle three"></div>
<div class="base"></div>
<div class="speaker"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .circle {
    background: #191919;
    border: 10px solid #5DBCF9;
    border-radius: 50%;
    border-top: 10px solid transparent;
    border-left: 10px solid transparent;
	position: absolute;
    transform: rotate(-45deg);
    
  }
  
  .one {
    height: 180px;
    width: 180px;
    right: 75
  }
  
  .two {
    height: 130px;
    width: 130px;
    right: 100
  }
  
  .three {
    height: 80px;
    width: 80px;
    right: 125
  }
  
  .speaker {
    width: 50px;
    height: 50px;
    position: absolute;
    right: 200px;
    border: 75px solid #5DBCF9;
    border-left: 75px solid #191919;
    border-top: 75px solid #191919;
    border-bottom: 75px solid #191919;
  }
  
  .base {
    background: #5DBCF9;
    height: 50px;
    width: 60px;
    border-radius: 10px;
    position: absolute;
    z-index: 4;
    left: 75
    
  }
  
</style>

```
