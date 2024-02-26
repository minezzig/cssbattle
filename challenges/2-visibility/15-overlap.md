# [15. Overlap](https://cssbattle.dev/play/15)

![](https://cssbattle.dev/targets/15.png)

```HTML

<div class="circles circle1"></div>
<div class="circles circle2"></div>
<div class="left-container">
  <div class="inner1"></div>
</div>
<div class="right-container">
  <div class="inner2"></div>
</div>



<style>
  body {
    background: #09042A;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .circles {
    height: 150px;
    width: 150px;
    border-radius: 50%;
    position: absolute;
    top: 75px;
  }

  .circle1 {
    background-color: #7B3F61;
    left: 75px;
  }

    .circle2 {
    background-color: #E78481;
    right: 75px;
      z-index: -4
  }

    .left-container {
    height: 150px;
    width: 26px;
    transform: translateX(-12px);
    overflow: hidden;
  }

  .right-container {
    height: 150px;
    width: 25px;
    position: absolute;
    transform: translateX(12px);
    overflow: hidden;
  }
  .inner1 {
    height: 150px;
    width: 150px;
    border-radius: 50%;
    background-color: #09042A;
  }

    .inner2 {
    height: 150px;
    width: 150px;
    border-radius: 50%;
    background-color: #09042A;
    position: absolute;
    right: 0;
  }
</style>
```
