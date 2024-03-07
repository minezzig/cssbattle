# [95. Pokeball](https://cssbattle.dev/play/95)

![](https://cssbattle.dev/targets/95.png)

```HTML
<div class="ball"></div>
<div class="bar"></div>
<div class="button"></div>
<style>
  body {
    background-color: #6CB3A9;
    display: flex;
    align-items: center;
    justify-content: center;
    box-sizing: border-box;
  }
  .ball {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: linear-gradient(#D25B70 0px, #D25B70 100px, #FFFFFF 100px, #FFFFFF 200px);
  }
  
  .bar {
    position: absolute;
    z-index: 1;
    width: 180px;
    height: 20px;
    background-color: #781728;
    border-left: 10px solid #6CB3A9;
    border-right: 10px solid #6CB3A9;
  }
  .button {
    position: absolute;
    z-index: 2;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    background-color: #F6DF96;
    border: 10px solid #781728;
  }
</style>
```
