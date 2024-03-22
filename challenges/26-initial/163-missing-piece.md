# [163. Missing Piece](https://cssbattle.dev/play/163)

![](https://cssbattle.dev/targets/163.png)

```HTML
<div></div>
<div class="right"></div>
<div class="bottom"></div>
<style>
  body {
    background: #D669EC;
    display: grid;
    place-items: center;
  }
  div {
    width: 100px;
    height: 100px;
    background: #FDFBF8;
    position: absolute;
    top: 40px;
    left: 90px;
    clip-path: polygon(
      0 0, 54% 0, 100% 46%, 100% 100%, 46% 100%, 0 54%
    );
  }
  .right {
    position: absolute;
    left: 210px;
    rotate: 90deg;
  }
  .bottom {
    position: absolute;
    top: 160px;
    rotate: 90deg;
  }
</style>
```
