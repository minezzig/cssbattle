# [46. Mountains](https://cssbattle.dev/play/46)

![](https://cssbattle.dev/targets/46.png)

```HTML
<div class="circle">
 <div class="mountain small"></div>
  <div class="mountain big"></div>
</div>
<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .circle {
    background: #FFF1C1;
    height: 200px;
    width: 200px;
    border-radius: 50%;
    overflow: hidden;
    position: absolute;
  }
  
  .mountain {
    background: #FE5F55;
    transform: rotate(-45deg)
  }
  
  .small {
    height: 50px;
    width: 50px;
    position: relative;
    top: 140px;
    left: 5px;
  }
  
  .big {
    height: 150px;
    width: 190px;
    position: relative;
    top: 54px;
    left: 32px;
  }
  

</style>

```
