# [83. Supernova](https://cssbattle.dev/play/83)

![](https://cssbattle.dev/targets/83.png)

```HTML
<div class="square"></div>
<div class="circle"></div>
  <div class="flower1"></div>
  <div class="flower2"></div>
  <div class="flower3"></div>
  <div class="flower4"></div>



<style>
  body {
    background-color: #243D83;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .flower1 {
    height: 100px;
    width: 100px;
    border-radius: 50%;
    background-color: #6592CF;
    position: absolute;
	top: 57px;
    left: 108px;  
  }
    .flower2 {
    height: 100px;
    width: 100px;
    border-radius: 50%;
    background-color: #6592CF;
    position: absolute;
	top: 57px;
    right: 108px;  
  }
    .flower3 {
    height: 100px;
    width: 100px;
    border-radius: 50%;
    background-color: #6592CF;
    position: absolute;
	bottom: 57px;
    left: 108px;  
  }
    .flower4 {
    height: 100px;
    width: 100px;
    border-radius: 50%;
    background-color: #6592CF;
    position: absolute;
	bottom: 57px;
    right: 108px;  
  }
  
  .square {
    height: 120px;
    width: 120px;
    background-color: #243D83;
    z-index: 2;
    transform: rotate(45deg);
  }
  
  .circle {
    background-color: #EEB850;
    height: 60px;
    width: 60px;
    position: absolute;
    z-index: 3;
    border-radius: 50%;
  }
</style>
```
