# [12. Wiggly Moustache](https://cssbattle.dev/play/12)

![](https://cssbattle.dev/targets/12.png)

```html
<div class="container-left">
  <div class="circle left"></div>
</div>
<div class="middle-container">
	<div class="circle center"></div>
</div>
<div class="container-right">
  <div class="circle right"></div>
</div>
<div class="cap1"></div>
<div class="cap2"></div>

<style>
  body {
    background-color: #F5D6B4;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle{
	background-color: #F5D6B4;
  	border:20px #D86F45 solid;
    height: 60px;
    width: 60px;
    border-radius: 50%;
  }

  .right {
    bottom: 0;
  }
 
  .center {
    z-index: 1;
  }
  
  .container-right {
	overflow: hidden;
    height: 50px;
    transform: translateY(25px) translateX(-20px) rotate(180deg);
  }
  
   .container-left {
	overflow: hidden;
    height: 50px;
    transform: translateY(25px) translateX(20px) rotate(180deg);
  }
  
    .middle-container {
	overflow: hidden;
    height: 50px;
    transform: translateY(-25px);				 
  }
  
  .cap1 {
    background-color: #D86F45;
    border-radius: 50%;
    height: 20px;
    width: 20px;
    position: absolute;
    left: 70px;
  }
  
    .cap2 {
    background-color: #D86F45;
    border-radius: 50%;
    height: 20px;
    width: 20px;
    position: absolute;
    right: 70px;
  }
</style>
```
