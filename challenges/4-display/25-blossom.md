# [25. Blossom](https://cssbattle.dev/play/25)

![](https://cssbattle.dev/targets/25.png)

```HTML
<div class="top-left"></div>
<div class="top-right"></div>
<div class="bottom-left"></div>
<div class="bottom-right"></div>
<style>
  body {
    background: #998235;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .top-left {
    background: #1A4341;
    height: 100px;
    width: 80px;
    border-radius: 0px 50px;
    position: absolute;
    top: 60px;
    left: 110px;
  }

  .bottom-right {
    background: #1A4341;
    height: 100px;
    width: 80px;
    border-radius: 50px 0px;
    position: absolute;
    bottom: 60px;
    right: 110px;
  }

  .top-right {
    background: #F3AC3C;
    height: 60px;
    width: 80px;
    border-radius: 50px 0px;
    position: absolute;
    top: 60px;
    right: 110px;
  }

 .bottom-left {
    background: #F3AC3C;
    height: 60px;
    width: 80px;
    border-radius: 0px 50px;
    position: absolute;
    bottom: 60px;
    left: 110px;
  }
</style>
```
