# [112. Chevron](https://cssbattle.dev/play/112)

![](https://cssbattle.dev/targets/112.png)

```HTML
<div class="left bottom"></div>
<div class="left middle"></div>
<div class="left top"></div>
<div class="right bottom"></div>
<div class="right middle"></div>
<div class="right top"></div>
<style>
  body {
    background: #6592CF;
    margin: 0;
  }

  div {
        width: 110px;
    height: 100px;
    position: absolute;
    background: transparent;
    border-bottom: 25px solid 
    #293D7E;
  }
  .left {
    border-left: 30px solid transparent;
    border-right: 20px solid transparent;
    right: 200px;
    transform-origin: bottom right;
    rotate: 39deg;
  }
  .bottom {
     bottom: 50px;
  }
  .middle {
    bottom: 100px;
  }
  .top {
    bottom: 150px;
  }
  .right {
    border-right: 30px solid transparent;
    border-left: 20px solid transparent;
    left: 200px;
    transform-origin: bottom left;
    rotate: -39deg;
  }
</style>
```
