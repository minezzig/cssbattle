# [55. Windmill](https://cssbattle.dev/play/55)

![](https://cssbattle.dev/targets/55.png)

```HTML
<div class="yellow-left"></div>
<div class="yellow-right"></div>
<div class="blue-top"></div>
<div class="blue-bottom"></div>


<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .yellow-left {
    border: 50px solid #F9E492;
    border-radius: 50%;
    border-left: 50px solid transparent;
    border-bottom: 50px solid transparent;
    transform: rotate(-45deg);
    position: absolute;
    left: 100px;
  }
  
  .yellow-right {
    border: 50px solid #F9E492;
    border-radius: 50%;
    border-right: 50px solid transparent;
    border-top: 50px solid transparent;
    transform: rotate(-45deg);
    position: absolute;
    right: 100px;
  }

  .blue-top {
    border: 50px solid #4F77FF;
    border-radius: 50%;
    border-right: 50px solid transparent;
    border-top: 50px solid transparent;
    transform: rotate(45deg);
    position: absolute;
    bottom: 50px;

  }
  
  .blue-bottom {
    border: 50px solid #4F77FF;
    border-radius: 50%;
    border-left: 50px solid transparent;
    border-bottom: 50px solid transparent;
    transform: rotate(45deg);
    position: absolute;
    top: 50px;
  }

</style>


```
