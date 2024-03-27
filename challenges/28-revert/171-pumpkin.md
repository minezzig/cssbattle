# [171. Pumpkin](https://cssbattle.dev/play/171)

![](https://cssbattle.dev/targets/171.png)

```HTML
<div class="stem"></div>
<div class="pumpkin"></div>
<style>
  body {
    background: #784972;
    display: grid;
    box-sizing: border-box;
    place-content: center;
  }
  .stem {
    position: absolute;
    width: 22px;
    height: 60px;
    border-radius: 25px;
    background: #F7FFCF;
    top: 50px;
    left: 189px;
    z-index: 100;
  }
  .pumpkin {
    position: absolute;
    width: 100px;
    height: 150px;
    background: #F7FFCF;
    border: 10px solid #784972;
    border-radius: 50%;
    top: 90px;
    left: 60px;
    -webkit-box-reflect: right 40px;
  }
  .pumpkin::before, .pumpkin::after {
    content: "";
    position: absolute;
    width: 100px;
    height: 150px;
    background: #F7FFCF;
    border: 10px solid #784972;
    border-radius: 50%;
  }
  .pumpkin::before {
    translate: 30px -10px;
  }
  .pumpkin::after {
    translate: 70px -10px;
  }
</style>

```
