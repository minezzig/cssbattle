# [29. Suffocate](https://cssbattle.dev/play/29)

![](https://cssbattle.dev/targets/29.png)

```HTML
<div class="star"></div>
<div class="circle top-left"></div>
<div class="circle top-right"></div>
<div class="circle bottom-left"></div>
<div class="circle bottom-right"></div>


<style>
  body {
    background-color: #F3AC3C;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .star {
    width: 150px;
    height: 150px;
    background: #1A4341;
    transform: rotate(-45deg); 
  }
  
  .circle {
    background: #F3AC3C;
    height: 200px;
    width: 200px;
    border-radius: 50%;
    position: absolute;
  }
  
  .top-left {
    top: -50;
    left: 0;
  }
  
  .top-right {
    top: -50;
    right: 0;
  }
  
  .bottom-left {
    bottom: -50;
    left: 0;
  }
  
  .bottom-right {
    bottom: -50;
    right: 0;
  }
</style>
```
