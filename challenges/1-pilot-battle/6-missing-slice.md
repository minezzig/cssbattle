# [6. Missing Slice](https://cssbattle.dev/play/6)

![](https://cssbattle.dev/targets/6.png)

```html
<div class="circle">
  <div class="top-left square"></div>
  <div class="top-right square"></div>
  <div class="bottom-left square"></div>
</div>
<style>
  body {
    margin: 0;
    background-color: #e3516e;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .circle {
    height: 200px;
    width: 200px;
    border-radius: 50%;
    position: absolute;
    overflow: hidden;
  }

  .square {
    height: 100px;
    width: 100px;
    float: left;
  }

  .top-left {
    background-color: #51b5a9;
  }

  .top-right {
    background-color: #fade8b;
    top: 0px;
    right: 50px;
  }

  .bottom-left {
    background-color: #f7f3d7;
  }
</style>
```
