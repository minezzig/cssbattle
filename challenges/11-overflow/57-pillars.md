# [57. Pillars](https://cssbattle.dev/play/57)

![](https://cssbattle.dev/targets/57.png)

```HTML
<div class="square"></div>
<div class="cut-out tl"></div>
<div class="yellow-dot tl"></div>
<div class="blue-dot tl"></div>
<div class="cut-out tr"></div>
<div class="yellow-dot tr"></div>
<div class="blue-dot tr"></div>
<div class="cut-out bl"></div>
<div class="yellow-dot bl"></div>
<div class="blue-dot bl"></div>
<div class="cut-out br"></div>
<div class="yellow-dot br"></div>
<div class="blue-dot br"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .cut-out {
    background: #191919;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: absolute;
  }
  
  .yellow-dot {
    background: #F9E492;
    height: 45px;
    width: 45px;
    border-radius: 50%;
    position: absolute;
  }
  
  .blue-dot {
    background: #4F77FF;
    height: 30px;
    width: 30px;
    border-radius: 50%;
    position: absolute;
  }
  
  .square {
    background: #4F77FF;
    height: 110px;
    width: 110px;
  }
  
  .tl {
    top: 75px;
    left: 125px;
  }
  
  .tr {
    top: 75px;
    right: 125px;
  }
  
  .bl {
    bottom: 75px;
    left: 125px;
  }
  
  .br {
    bottom: 75px;
    right: 125px;
  }
  
</style>


```
