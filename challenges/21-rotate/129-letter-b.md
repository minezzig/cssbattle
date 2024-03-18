# [129. Letter B](https://cssbattle.dev/play/129)

![](https://cssbattle.dev/targets/129.png)

```HTML
<div class="b top"></div>
<div class="b bottom"></div>
<style>
  body {
    background-color: #6592CF;
    margin: 0;
  }
  .b, ::before, ::after {
    width: 100px;
    height: 80px;
    background: #060F55;
    border-radius: 0 40px 40px 0;
    position: absolute;
  }
  .top {
    top: 80px;
    left: 110px;
  }
  .top::before {
    z-index: -1;
    content: "";
    background-color: #2E3B9F;
    left: 40px;
  }.top::after {
    z-index: -2;
    content: "";
    background-color: #515DBD;
    left: 80px;
  }
  .bottom {
    top: 140px;
    left: 110px;
  }
    .bottom::before {
    z-index: -1;
    content: "";
    background-color: #2E3B9F;
    left: 40px;
  }.bottom::after {
    z-index: -2;
    content: "";
    background-color: #515DBD;
    left: 80px;
  }
</style>
```
