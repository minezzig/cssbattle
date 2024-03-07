# [90. Eclipse](https://cssbattle.dev/play/90)

![](https://cssbattle.dev/targets/90.png)

```HTML
<div class="center"></div>
<div class="top"></div>
<div class="bottom"></div>
<style>
  body {
    background-color: #F3AC3C;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .center {
    height: 200px;
    width: 200px;
    border-radius: 50%;
    background-color: #1A4341;
    border: 25px solid #F3AC3C;
    z-index: 2;
  }
  
  .top {
    z-index: 1;
    width: 400px;
    height: 400px;
    border-radius: 50%;
    position: absolute;
    background-color: #998235;
    top: -250px;
  }
  
    .bottom {
    z-index: 3;
    width: 400px;
    height: 400px;
    border-radius: 50%;
    position: absolute;
    background-color: #998235;
    bottom: -250px;
  }
</style>
```
