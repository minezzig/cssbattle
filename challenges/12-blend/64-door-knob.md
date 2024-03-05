# [64. Door Knob](https://cssbattle.dev/play/64)

![](https://cssbattle.dev/targets/64.png)

```HTML
<div class="circle"></div>
<div class="smile"></div>
<div class="dimple one"></div>
<div class="dimple two"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .circle {
    background: #E08027;
	border: 30px solid #824B20;
    border-radius: 50%;
    height: 100px;
    width: 100px;
  }

  .smile {
    border: 20px solid #FFF58F;
    border-radius: 50%;
    border-top: 20px solid transparent;
    border-right: 20px solid transparent;
    height: 80px;
    width: 80px;
    position: absolute;
    transform: rotate(-45deg);
  }
  
  .dimple {
    background: #FFF58F;
    border-radius: 50%;
    position: absolute;
  }
  
  .one {
    height: 20px;
    width: 20px;
    left: 140px;
  }
  
  .two {
    height: 20px;
    width: 20px;
    right: 140px;
  }
</style>

```
