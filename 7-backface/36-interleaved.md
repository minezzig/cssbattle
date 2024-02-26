# [36. Interleaved](https://cssbattle.dev/play/36)

![](https://cssbattle.dev/targets/36.png)

```HTML
<div class="yellow y1"></div>
<div class="yellow y2"></div>
<div class="yellow y3"></div>
<div class="green g1"></div>
<div class="green g2"></div>

<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .yellow {
    background: #F3AC3C;
    width: 50px;
    height: 200px;
    border-radius: 50px 50px 0 0;
    position: absolute;
    bottom: 0;
  }

  .green {
    background: #998235;
    width: 50px;
    height: 200px;
    border-radius: 0 0 50px 50px;
    position: absolute;
    top: 0;
  }

  .y1 {
    left: 25px;
  }

  .y3 {
    right: 25px;
  }

  .g1 {
    left: 100px;
  }

  .g2 {
    right: 100px;
  }


</style>

```
