# [141. Third Eye](https://cssbattle.dev/play/141)

![](https://cssbattle.dev/targets/141.png)

```HTML
<div class="top"></div>
<div class="middle"></div>
<div class="bottom"></div>

<style>
  body {
    margin: 0;
    background: #E3516E;
  }
  .top, .bottom {
    background: #D9D9D9;
    height: 150px;
    width: 150px;
    border-radius: 50%;
    position: absolute;
  }
  .top {
    top: -75px;
    left: -75px;
  }
  .bottom {
    bottom: -75px;
    right: -75px;
  }
  .middle {
    width: 100px;
    height: 100px;
    background: #D9D9D9;
    border-radius: 100px 0;
    position: absolute;
    left: 150px;
    top: 100px;
    rotate: 45deg;
  }
</style>

```
