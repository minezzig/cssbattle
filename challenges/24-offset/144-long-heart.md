# [144. Long Heart](https://cssbattle.dev/play/144)

![](https://cssbattle.dev/targets/144.png)

```HTML
<div class="tube left"></div>
<div class="tube bottom"></div>
<div class="ball"></div>
<div class="rec"></div>
<style>
  body {
    margin: 0;
    padding: 0;
    background: #62306D;
    box-sizing: border-box;
  }
  .rec {
    background: #62306D;
    border-radius: 25px;
    height: 100px;
    width: 100px;
    position: absolute;
    left: 75px;
    top: 125px;
  }
  .ball {
    height: 50px;
    width: 50px;
    background: #F7EC7D;
    border-radius: 50%;
    position: absolute;
    left: 60px;
    bottom: 50px;
  }
  .tube {
    background-color: #F7EC7D;
    width: 75px;
    height: 200px;
    border-radius: 50px 50px 0 0;
    position: absolute;
  }
  .left {
    top: 100px;
  }
  .bottom {
    transform-origin:  bottom right;
    rotate: 90deg;
    bottom: 0;
    left: -75px;
  }
</style>
```
