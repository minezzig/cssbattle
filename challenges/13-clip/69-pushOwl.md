# [69. PushOwl](https://cssbattle.dev/play/69)

![](https://cssbattle.dev/targets/69.png)

```HTML

<div class="left"></div>
<div class="right"></div>
<div class="pupil-left"></div>
<div class="pupil-right"></div>
<div class="nose"></div>
<div class="eye-left"></div>
<div class="eye-right"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    border: 0;
  	display: flex;
    justify-content: center;
    align-items: center;
  }
  .left {
    width: 115px;
    height: 115px;
    background: #E08027;
    border-radius: 0 50% 50% 50%;
    position: absolute;
    top: 77px;
    left: 89px;
  }
  .right {
    width: 115px;
    height: 115px;
    background: #E08027;
    border-radius: 50% 0 50% 50%;
    border: 10px solid #191919;
    position: absolute;
    top: 67px;
    right: 79px;
  }
  .pupil-left {
    background: #191919;
    height: 90px;
    width: 90px;
    position: absolute;
    border-radius: 50%;
    left: 100px;
    top: 89px;
  }
    .pupil-right {
    background: #191919;
    height: 90px;
    width: 90px;
    position: absolute;
    border-radius: 50%;
    right: 101px;
    top: 89px;
  }
  .nose {
    background: #E08027;
    position: absolute;
    height:50px;
    width: 58px;
    z-index: -3;
    transform: rotate(45deg);
    bottom: 90px;
    left: 168px;
  }
  .eye-left {
    background: #191919;
    border: 9px solid #E08027;
    position: absolute;
    height: 12px;
    width: 12px;
    border-radius: 50%;
    left: 131px;
    top: 125px;
    border-right: 9px solid transparent;
    border-bottom: 9px solid transparent;
    transform: rotate(45deg)
  }
    .eye-right {
    background: #191919;
    border: 9px solid #E08027;
    position: absolute;
    height: 12px;
    width: 12px;
    border-radius: 50%;
    right: 131px;
    top: 125px;
    border-right: 9px solid transparent;
    border-bottom: 9px solid transparent;
    transform: rotate(45deg)
  }
</style>

```
