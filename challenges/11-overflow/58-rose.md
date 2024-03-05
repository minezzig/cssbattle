# [48. Rose](https://cssbattle.dev/play/58)

![](https://cssbattle.dev/targets/58.png)

```HTML
<div class="stick"></div>
<div class="base"></div>
<div class="cup"></div>
<div class="bottom-layer"></div>
<div class="top-layer"></div>
<div class="ball"></div>


<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .stick {
    background: #F9E492;
    height: 100px;
    width: 20px;
    position: absolute;
	bottom: 45px;
    border-radius: 50px;
  }
   
  .base {
    background: #F9E492;
    height: 40px;
    width: 40px;
    position: absolute;
	bottom: 115px;
    border-radius: 50%;
  }
  
  .cup {
	background: #4F77FF;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    top: 65px;
  }
  
  .bottom-layer {
    background: #4F77FF;
    border: 10px solid #191919;
    height: 30px;
    width: 140px;
    border-radius: 20px 20px 50px 50px;
    z-index: 2;
    position: absolute;
    top: 75px;
  }
  
  .top-layer {
    background: #4F77FF;
    border: 10px solid #191919;
    height: 30px;
    width: 100px;
    border-radius: 20px 20px 50px 50px;
    z-index: 2;
    position: absolute;
    top: 55px;
  }
  
  .ball {
    background: #4F77FF;
    border: 10px solid #191919;
    height: 30px;
    width: 30px;
    border-radius: 50%;
    z-index: 2;
    position: absolute;
    top: 35px;
  }
</style>


```
