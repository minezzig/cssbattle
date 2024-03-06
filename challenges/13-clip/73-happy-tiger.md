# [73. Happy Tiger](https://cssbattle.dev/play/73)

![](https://cssbattle.dev/targets/73.png)

```HTML
<div class="ear-left"></div>
<div class="ear-right"></div>
<div class="head"><p class="mark"></p></div>
<div class="eyes-left"></div>
<div class="eyes-right"></div>
<div class="mouth"></div>
<div class="whisker-left"></div>
<div class="whisker-right"></div>
<div class="septum"></div>




<style>
  body {
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #F3AC3C;
  }
  
  .head {
    background: #998235;
    height: 150px;
    width: 150px;
    border-radius: 50% 50% 40% 40%;
    overflow: hidden;
  }
  .mark {
    background: #1A4341;
    height: 50px;
    width: 50px;
    position: relative;
    top: -50px;
    left: 50px;
    transform: rotate(45deg);  
  }
  .ear-left {
    background: radial-gradient(#1A4341 45%, #998235 50%);
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: absolute;
    top: 65px;
    left: 115px;
    z-index: -1;
  }
  .ear-right {
    background: radial-gradient(#1A4341 45%, #998235 50%);
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: absolute;
    top: 65px;
    right: 115px; 
    z-index: -1;
  }
  .eyes-left {
    background: #1A4341;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
    left: 150px;
    top: 135px;  
    -webkit-box-reflect: right 60px;;
  }  
  .mouth {
    background: white;
    width: 100px;
    height: 40px;
    position: absolute;
    bottom: 90px;
    border-radius: 15px 15px 40px 40px
  }
  .whisker-left {
    background: transparent;
    height: 20px;
    width: 20px;
    position: absolute;
    bottom: 100px;
    left:165px;
    border-radius: 50%;
    border: 10px solid #1A4341;
    border-top-color: transparent;
    border-left-color: transparent;
    transform: rotate(45deg);
  }
  .whisker-right {
    background: transparent;
    height: 20px;
    width: 20px;
    position: absolute;
    bottom: 100px;
    right:165px;
    border-radius: 50%;
    border: 10px solid #1A4341;
    border-top-color: transparent;
    border-left-color: transparent;
    transform: rotate(45deg);
  }
  .septum {
    background: #1A4341;
    width: 10px;
    height: 20px;
    position: absolute;
    bottom: 120px;
  }
</style>
```
