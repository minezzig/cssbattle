# [78. Ukulele](https://cssbattle.dev/play/78)

![](https://cssbattle.dev/targets/78.png)

```HTML
<div class="back"></div>
<div class="front"></div>
<div class="neck"></div>
<div class="top"></div>
<div class="fret"></div>
<div class="hole"></div>
<div class="tips"></div>

<style>
  body {
    background-color: #F3AC3C;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .back {
    background-color: #998235;
    height: 120px;
    width: 120px;
    border-radius: 50%;
    position: absolute;
    left: 45px;
  }
  
  .front {
    background-color: #998235;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    left: 115px;
  }
  
  .neck {
    background-color: #1A4341;
    height: 20px;
    width: 120px;
    position: absolute;
    left: 200px;
    z-index: -1;
  }
  
  .top {
    background-color: #998235;
    height: 30px;
    width: 40px;
    border-radius: 10px;
    position: absolute;
    right: 45px;
  }
  
  .fret {
    background-color: #1A4341;
    height: 40px;
    width: 10px;
    border-radius: 20px;;
    z-index: 1;
    position: absolute;
    left: 85px;
    
  }
  
  .hole {
    background: #1A4341;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    border: solid 5px #F3AC3C;
    z-index: 3;
    position: absolute;
    left: 140px;
  }
  
  .tips {
    background-color: #1A4341;
    height: 4px;
    width: 20px;
    z-index: 4;
    border-radius: 10px;
    position: absolute;
    right: 55px;
    top: 143px;
  }
  .tips::after {
    content: "";
    background-color: #1A4341;
    height: 4px;
    width: 20px;
    z-index: 4;
    border-radius: 10px;
    position: absolute;
    top: 10px;
    
  }
```
