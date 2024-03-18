# [132. Letter S](https://cssbattle.dev/play/132)

![](https://cssbattle.dev/targets/132.png)

```HTML
<div class="top"></div>
<div class="bar"></div>
<div class="bottom"></div>
<style>
  body {
    background: #4F77FF;
    margin: 0;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
    gap: 20px;
  }
  .top, .bottom {
    width: 240px;
    height: 50px;
    background: #FFFFFF;
    border-radius: 10px;
  }
  .top {
    box-shadow: 20px -20px 0 0 #1038BF;
  }
  .bottom {
    box-shadow: -20px 20px 0 0 #1038BF;
  }
  .bar {
    width: 240px;
    height: 20px;
    background: #FFFFFF;
    border-radius: 10px;
    position: relative;
  }
  .bar::before, .bar::after{
    content: "";
    position: absolute;
    width: 20px;
    height: 60px;
    background: #FFFFFF;
    border-radius: 10px;
  }
  .bar::before {
    bottom: 0;
  }
  .bar::after {
    top: 0;
    right: 0;
  }
  }
</style>
```
