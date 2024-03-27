# [167. React India](https://cssbattle.dev/play/167)

![](https://cssbattle.dev/targets/167.png)

```HTML

  <div class="dot"></div>
  <div class="ellipse"></div>

<style>
  body {
    background: #0D1335;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    box-sizing: border-box;
  }

  .dot {
    position: absolute;
    background: #73C6EA;
    height: 40px;
    aspect-ratio: 1;
    border-radius: 50%;
  }
  .ellipse, .ellipse::before, .ellipse::after{3126
    background: transparent;
    border: 10px solid var(--color);
    height: 230px;
    width: 90px;
    border-radius: 50%;
  }
  .ellipse {
    --color: #FBFAE2;
    position: relative;
    rotate: 90deg;
  
  }
   .ellipse::before {
     position: absolute;
     translate: -10px -10px;
    content: "";
    --color: #DC6638;
     rotate: 60deg;
     z-index: -1;
  }
   .ellipse::after {
     position: absolute;
     translate: -10px -10px;
     content: "";
    --color: #4FA07B;
     rotate: -60deg;
     z-index: -2;
  }

</style>
```
