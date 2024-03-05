# [56. Skull](https://cssbattle.dev/play/56)

![](https://cssbattle.dev/targets/56.png)

```HTML
<div class="jaw"></div>
<div class="skull"></div>
<div class="eyes"></div>
<div class="nose"></div>
<div class="teeth"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .skull {
    background: #4F77FF;
    height: 100px;
    width: 120px;
    border-radius: 100px 100px 10px 10px;
    position: absolute;
    bottom: 115px;
  }
  
  .jaw {
    background: #4F77FF;
    height: 80px;
    width:  80px;
    position: absolute;
    border-radius:20px;
    bottom: 85px;
  }
  
  .eyes {
    background: #191919;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    position: absolute;
	top: 138px;
    left: 155px;
  }
  
  .eyes:after {
    content: "";
    background: #191919;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    position: absolute;
	left: 50px;	
  }
  
  .nose {
    background: #191919;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
	bottom: 104px;
  }
  
  .teeth {
    background: #191919;
    height: 20px;
    width: 10px;
    border-radius: 50px;
    position: absolute;
    top: 205px;
  }
  
  .teeth:before, .teeth:after {
    content: "";
    background: #191919;
    height: 20px;
    width: 10px;
    border-radius: 50px;
    position: absolute;
    right: 15px;
  }
  
  .teeth:after{
    left: 15px;
  }
</style>
```
