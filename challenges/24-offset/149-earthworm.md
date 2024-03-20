# [149. Earthworm](https://cssbattle.dev/play/149)

![](https://cssbattle.dev/targets/149.png)

```HTML
<div class="tube left"></div>
<div class="tube middle"></div>
<div class="tube right"></div>
<div class="tube bottom"></div>
<div class="ball one"></div>
<div class="ball two"></div>
<div class="ball three"></div>
<div class="square uno"></div>
<div class="square dos"></div>
<div class="square tres"></div>

<style>
  body {
    margin: 0;
    padding: 0;
    background: #E38F66;
  }

  .ball {
    background: #FFFBDA;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
  }

  .one {
    left: 30px;
    top: 170px;
  }

  .two {
    left: 70px;
    bottom: 70px;
  }

  .three {
    left: 110px;
    bottom: 30px;
  }

  .square {
    background: #E38F66;
    height: 50px;
    width: 50px;
    border-radius: 10px;
    position: absolute;
  }

  .uno {
    left: 40px;
    top: 130px;
  }

  .dos {
    left: 30px;
    bottom: 30px;
  }
    .tres {
    left: 120px;
    bottom: 40px 
  }
  .tube {
    background: #FFFBDA;
    height: 120px;
    width: 40px;
    position: absolute;
  }
  .left {
    border-radius: 40px 40px 0 40px;
    top: 100px;
  }
  .middle {
    rotate: 90deg;
    bottom: 100px;
    height: 100px;
    transform-origin: bottom;
    border-radius: 40px 0 40px 40px;
  }

  .right {
    border-radius: 40px 40px 0 40px;
    left: 80px;
    bottom: 0;
  }

  .bottom {
    rotate: 90deg;
    transform-origin: bottom right;
    border-radius: 40px 40px 40px 0;
    height: 110px;
    bottom: 0;
    left: 50px;
  }
</style>

```
