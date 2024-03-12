# [108. Clow Card](https://cssbattle.dev/play/108)

![](https://cssbattle.dev/targets/108.png)

```HTML
<div class="rectangle">
<div class="stripes"></div>  
  <div class="in1"></div>
  <div class="in2">
    <div class="big-ring"></div>
    <div class="small-ring"></div>
    <div class="center"></div>
  </div>
</div>

<style>
  body {
    background-color: #000000;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .stripes {
    background: linear-gradient(to right, #EBAE11 10px 50px, #E96A23 50px 64px, #EBAE11 64px);
    position: absolute;
    z-index: ;
    top: -100px;
    left: 113px;
    height: 300px;
    width: 89px;
    margin: auto;
    transform: rotate(15deg)
  }
  .rectangle {
    width: 300px;
    height: 150px;
    background: #E96A23;
    position: relative;
    overflow: hidden;
  }
  .in1 {
    background-color: #000000;
    height: 90px;
    width: 270px;
    position: absolute; 
    border-radius: 13px;
    top: 30px;
    left: 15px;
  }
  .in2 {
    background-color: #000000;
    height: 120px;
    width: 240px;
    position: absolute; 
    top: 15px;
    left: 30px;
    border-radius: 13px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .big-ring {
    border: 5px solid #EBAE11;
    height: 80px;
    width: 200px;
    border-radius: 100%;
  }
  .small-ring {
    border: 5px solid #EBAE11;
    height: 60px;
    width: 120px;
    border-radius: 100%;
    position: absolute;
  }
  .center {
    background-color: #EBAE11;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
  }
</style>

```
