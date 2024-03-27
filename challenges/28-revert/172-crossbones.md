# [172. Crossbones](https://cssbattle.dev/play/172)

![](https://cssbattle.dev/targets/172.png)

```HTML
<div class="stick one"></div>
<div class="stick two"></div>
<style>
  body {
    background: #EFEB99;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .stick {
    width: 30px;
    height: 190px;
    position: absolute;
    background: #8647E6;
    bottom: 70px;
  }
  .stick::before, .stick::after{
    content: "";
    height: 30px;
    aspect-ratio: 1;
    background: #8647E6;
    border-radius: 50%;
    position: absolute;
  }

  .stick::before {
    bottom: -12px;;
    left: -16px;
    box-shadow: 30px 0px 0 #8647E6;
  }
  .stick::after {
    top: -15px;;
    left: -16px;
    box-shadow: 30px 0px 0 #8647E6;
  }
  .one {
    left: 113px;
    transform-origin: bottom right;
    rotate: 45deg;
  }
  .two {
    right: 113px;
    transform-origin: bottom left;
    rotate: -45deg;
  }
</style>

```
