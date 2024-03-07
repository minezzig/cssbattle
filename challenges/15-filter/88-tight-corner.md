# [88. Tight Corner](https://cssbattle.dev/play/88)

![](https://cssbattle.dev/targets/88.png)

```HTML
<div class="bar left"></div>
<div class="bar right"></div>
<div class="middle"></div>

<style>
  body {
    background-color: #F7F3DA;
    margin: 0;
    padding: 0;
  }  
  
  .bar {
    background-color: #D25B70;
    height: 40px;
    width: 210px;
    border-radius: 10px;
  }
  
  .left {
    position: absolute;
    top: 110px;    
    right: 200px;
  }
  
  .left::after {
	content: " ";
    background-color: #F7F3DA;
    height: 40px;
    width: 200px;
    z-index: 4;
    position: absolute;
    left: 210px;
    border-radius: 30px;
  }
  
  .right {
    position: absolute;
    bottom: 110px;
    left: 200px;
  }
  
  .right::after {
    content: " ";
    background-color: #F7F3DA;
    height: 40px;
    width: 210px;
    z-index: 4;
    position: absolute;
    right: 210px;
    border-radius: 30px;
  }
  
  .middle {
    height: 30px;
    width: 30px;
    background-color: #D25B70;
    position: absolute;
    left: 185px;
    top: 135px;
  }
</style>
```
