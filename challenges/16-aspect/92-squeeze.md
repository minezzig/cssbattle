# [92. Squeeze](https://cssbattle.dev/play/92)

![](https://cssbattle.dev/targets/92.png)

```HTML
<div class="circle"></div>
<div class="bar"></div>
<div class="round left"></div>
<div class="round right"></div>

<style>
 body {
    background-color: #6592CF;
    margin: 0;
   display: flex;
   align-items: center;
   justify-content: center;
 }
  .circle, 
  .circle::before, 
  .circle::after {
    width: 200px;
    aspect-ratio: 1;
    border-radius: 50%;
    background: #243D83;
    positon: relative;
  }
  .circle::before {
    content: "";
    position: absolute;
    left: -126px;;
  }
  .circle::after {
    content: "";
    position: absolute;
    right: -125px;
  }

  .bar {
    height: 36px;
    width: 100%;
    left: 0;
    top: 50%;
    translate: 0 -50%;
    position: absolute;
    background-color: #243D83;
  }

   .round, .round::after {
    z-index: 5;
    background-color: #6592CF;
    height: 32px;
    aspect-ratio: 1;
    border-radius: 50%;
    position: absolute;
    background: #6592CF;
  } 
  .round::after {
    content: "";
    width: 32px;
    top: 52px;
    position: absolute;
  } 
  .left {
    left: 71px;
    top: 108px;
  } 
  .right {
    right: 71px;
    top: 108px;
  }

</style>
```
