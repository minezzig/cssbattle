# [121. Duck Hunt](https://cssbattle.dev/play/121)

![](https://cssbattle.dev/targets/121.png)

```HTML
 <div class="trunk"></div>
<div class="shrub"></div>
<div class="tree"></div>
<div class="topper"></div>
<style>
  body {
    margin: 0;
    background: linear-gradient(to bottom, #1E92FF 0 180px, #69D10A 180px 220px, #6F6100 220px 100%)
  }
  .tree, .tree:before, .tree:after,
  .shrub, .shrub::after, .topper{
    background: #69D10A;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    position: absolute;
  }
  .topper {
    left: 40px;
    top: 60px;
  }
  .tree {
    left: 40px;
    top: 80px;
  }
  .tree::before {
    content: "";
    left: -20px;
  }
  .tree::after {
    content: "";
    left: 20px;
  }
  .shrub {
    right: 50px;
    top: 130px;
  }
  .shrub::after {
    content: "";
    bottom: -20px;
  }
  .trunk {
    width: 20px;
    height: 80px;
    background: #441A0A;
    position: absolute;
    bottom: 120px;
    left: 50px;
  }
</style>
```
