# [50. Use Hand Sanitizer](https://cssbattle.dev/play/50)

![](https://cssbattle.dev/targets/50.png)

```HTML
<div class="bottle"></div>
<div class="cap"></div>
<div class="tip"></div>
<div class="lever"></div>
<div class="spout"></div>
<div class="drops"></div>
<div class="drops two"></div>
<div class="liquid"></div>
<div class="wave"></div>

<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .bottle {
    background: #F3AC3C;
    height: 140px;
    width: 100px;
    position: absolute;
    bottom: 50px;
    border-radius: 20px;
  }
  .cap {
    background: #F3AC3C;
    height: 40px;
    width: 50px;
    position: absolute;
    top: 90px;
    border-radius: 10px;
  }
  
  .tip {
    background: #F3AC3C;
    height: 20px;
    width: 20px;
    position: absolute;
    top: 70px;
  }
  
  .lever {
    background: #F3AC3C;
    height: 20px;
    width: 150px;
    border-radius: 20px;
    position: absolute;
    top: 50px;
    right: 100px;
  }
  
  .spout {
    background: #F3AC3C;
    height: 40px;
    width: 20px;
    position: absolute;
    top: 50px;
    right: 100px;
    border-radius: 30px;
  }
  
  .drops {
    background: #998235;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
    top: 100px;
    right: 100px;
  }
  
  .two {
    top: 130px;
    right: 100px;
  }
  
  .liquid {
    background: #998235;
    height: 80px;
    width: 100px;
    position: absolute;
    bottom: 50px;
    border-radius: 0 0 20px 20px;
  }
  
  .wave {
    background: #998235;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
    top: 140px;
    left: 150px;
  }
  
  .wave:after {
    content: "";
    background: #F3AC3C;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
	left: 50px;
    
  }
</style>

```
