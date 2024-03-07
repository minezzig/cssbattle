# [86. Stairway](https://cssbattle.dev/play/86)

![](https://cssbattle.dev/targets/86.png)

```HTML
<div class="window">
  <div class="step one"></div>
  <div class="step two"></div>
  <div class="step three"></div>
  <div class="step four"></div>
</div>
<style>
  body {
   background-color: #191919;  
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0;
    padding: 0;
  }
  .window {
    width: 100px;
    height: 150px;
    background: #4F77FF;
    border-radius: 50px 50px 0 0;
    position: relative;
  }
  .step {
    height: 20px;
    width: 100px;
    position: absolute;
    background-color: #191919;
  }
  .one {
    bottom: 0;
    left: 20px
  }
  .two {
    bottom: 24px;
    left: 40px
  }
  .three {
    bottom: 48px;
    left: 60px
  }
  .four {
    bottom: 72px;
    left: 80px
  }
</style>
```
