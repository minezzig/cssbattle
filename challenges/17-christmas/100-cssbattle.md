# [100. CSSBattle](https://cssbattle.dev/play/100)

![](https://cssbattle.dev/targets/100.png)

```HTML
<div class="outer">
  <div class="knob"></div>
  <div class="inner">
    <div class="block">
      <div class="sword one"></div>
      <div class="sword two"></div>
    </div>
  </div>
</div>

<style>
  body {
    background-color: #14313E;
    margin: 0;
    box-sizing: border-box;
    display: grid;
    place-content: center;
  }
  .outer {
    width: 274px;
    height: 150px;
    background: #FFDF00;
    display: grid;
    place-content: center;
    border-radius: 20px;
    position: relative;
  }
  .knob {
    background: #FFDF00;
    width: 15px;
    height: 40px;
    position: absolute;
    left: -10px;
    top: 50%;
    translate: 0 -50%;
    border-radius: 5px;
    box-shadow: 279px 0 #FFDF00;
  }
  .inner {
    width: 224px;
    height: 100px;
    background: #14313E;
    border-radius: 10px;
    position: relative;
  }
  .block {
    height: 175px;
    width: 195px;
    background: #14313E;
    position: relative;
    top: -25px;
    left: 15px;
    z-index: 1
  }
  .sword {
    background: #FFDF00;
    height: 20px;
    width: 80px;
    transform-origin: top left;
  }
  .sword::before {
    content: "";
    height: 60px;
    background: #FFDF00;
    width: 20px;
    position: absolute;
    border-radius: 0 0 8px 8px;
    left: 30px
  }
    .sword::after {
    content: "";
    height: 150px;
    background: #FFDF00;
    width: 30px;
    position: absolute;
    left: 25px;
    top: -150;
    clip-path: polygon(
      15px 0, 100% 15px, 100% 100%, 0 100%, 0 15px
    )
  }
  .one {
    position: absolute;
    bottom: 25px;
    left: 101px;
    rotate: -45deg;
  }
  .two {
    position: absolute;
    bottom: 80px;
    left: 35px;
    rotate: 45deg;
    z-index: -1;
  }

  .sword.two::after {
    background: linear-gradient(#FFDF00, #FFDF00 77px, #14313E 77px, #14313E 126px, #FFDF00 126px, #FFDF00 );
  }

</style>


```
