# [175. Evil Cat](https://cssbattle.dev/play/175)

![](https://cssbattle.dev/targets/175.png)

```HTML
<div class="face">
  <div class="ear left-ear"></div>
  <div class="ear right-ear"></div>
  <div class="eye left-eye"></div>
  <div class="eye right-eye"></div>
</div>
<style>
  body {
    background: #ED6A9D;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .face {
    width: 180px;
    height: 150px;
    background: #050044;
    translate: 0 15px;
    border-radius: 50%;
    position: relative;
  }
  .face::after {
    content: "";
    width: 0;
    height: 0;
    border-top: 15px solid #ED6A9D;
    border-left: 15px solid transparent;
    border-right: 15px solid transparent;
    position: absolute;
    left: 75px;
    top: 95px;
  }
  .ear {
    height: 0;
    aspect-ratio: 1;
    border-bottom: 60px solid #050044;
    border-left: 30px solid transparent;
    border-right: 30px solid transparent;
    position: absolute;
    transform-origin: top;
  }
  .left-ear {
    left: -20px;
    top: -25px;
    rotate: -30deg;
  }
  .right-ear {
    right: -20px;
    top: -25px;
    rotate: 30deg;
  }
  .eye {
    position: absolute;
    background: #FFC100;
    width: 40px;
    aspect-ratio: 1;
    top: 40px;
    border-radius: 0 20px 0 20px;
    rotate: -45deg;
  }
  .eye::before{
    content: "";
    background: #050044;
    height: 30px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    inset: 50%;
    translate: -50% -50%;
    rotate: 45deg;
  }
  .left-eye {
    left: 35px;
  }
  .right-eye {
    right: 35px;
  }
</style>

```
