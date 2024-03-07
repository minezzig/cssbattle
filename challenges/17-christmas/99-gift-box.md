# [99. Gift Box](https://cssbattle.dev/play/99)

![](https://cssbattle.dev/targets/99.png)

```HTML
<div class="bow"></div>
<div class="box"></div>
<div class="box4"></div>
<style>
  body {
    background-color: #AC474B;
    margin: 0;
    padding: 0;

  }
  .bow {
    border: 10px solid white;
    border-radius: 50% 50% 0 50%;
    width: 20px;
    height: 20px;
    position: absolute;
    top: 50px;
    left: 165px;
  }
    .bow::after {
    content: "";
    border: 10px solid #ffffff;
    border-radius: 50% 50% 50% 0;
  	position: absolute;
    width: 20px;
    height: 20px;
    transform: translate(20px, -10px); 
  }
  .box {
    background-color: #ffffff;
    height: 60px;
    width: 60px;
 	position: absolute;
    top: 110px;
    left: 130px;  
  }
  
    .box::before {
    content: "";
    background-color: #ffffff;
    height: 60px;
    width: 60px;
    position: absolute;
    top: 80px;
  }
  .box::after {
    content: "";
    background-color: #ffffff;
    height: 60px;
    width: 60px;
    position: absolute;
    left: 80px;
  }
    .box4 {
    content: "";
    background-color: #ffffff;
    height: 60px;
    width: 60px;
    position: absolute;
    bottom: 50px;
    right: 130px;
  }
</style>


```
