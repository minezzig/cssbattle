# [44. Stripes](https://cssbattle.dev/play/44)

![](https://cssbattle.dev/targets/44.png)

```HTML
<div class="rectangle"></div>
<div class="circle left"></div>
<div class="circle right"></div>
<div class="bar"></div>
<div class="bar b"></div>
<div class="bar c"></div>
<div class="bar d"></div>


<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .rectangle {
    background: #F3AC3C;
    height: 180px;
    width: 160px;
  }
  
  .circle {
    background: #1A4341;
    height: 300px;
    width: 300px;
    border-radius: 50%;
    position: absolute;
  }
  
  .left {
    right: 250px;
  }
  
  .right {
    left: 250px;
  }
  
  .bar {
    background: #1A4341;
    height: 20px;
    width: 400px;
    position: absolute;
    top: 80px;
  }
  
  .b {
    top: 120px;
  }
  
  .c {
    top: 160px;
  }
  
  .d {
    top: 200px;
  }
  
</style>
```
