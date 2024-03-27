# [177. Frankenstein](https://cssbattle.dev/play/177)

![](https://cssbattle.dev/targets/177.png)

```HTML
<div class="hair"></div>
<div class="face">
  <div class="eye"></div>
  <div class="mouth"></div>
  <div class="bolt"></div>
</div>
<style>
  body {
    background: #3C8D3F;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .hair {
    height: 30px;
    width: 150px;
    background: #1A1D2F;
    position: relative;
    border-radius: 10px 10px 0 0;
  }
  .hair::after {
    content: "";
    width: 150px;
    height: 15px;
    background: #1A1D2F;
    position: absolute;
    translate: 0 30px;
    z-index: 10;
    clip-path: polygon(0 0,
      15px 15px,
      30px 0px,
      45px 15px,
      60px 0px,
      75px 15px,
      90px 0px,
      105px 15px,
      120px 0px,
      135px 15px,
      150px 0px);
  }
  .face {
    width: 150px;
    height: 120px;
    background: #14F078;
    border-radius: 0 0 100px 100px;
    position: relative;

  }
  .eye {
    position: absolute;
    width: 30px;
    aspect-ratio: 1;
    background: #1A1D2F;
    border-radius: 50%;
    top: 40px;
    left: 30px;
    box-shadow: 60px 0 #1A1D2F;
  }
  .eye::after {
    content: "";
    position: absolute;
    height: 10px;
    aspect-ratio: 1;
    background: #FFFFFF;
    border-radius: 50%;
    inset: 10px;
    box-shadow: 60px 0 #FFFFFF;
  }
  .mouth {
    width: 40px;
    height: 20px;
    border-radius: 0 0 100px 100px;
    background: #1A1D2F;
    position: absolute;
    bottom: 20px;
    left: 55px;
  }

  .bolt {
    background: #1A1D2F;
    height: 30px;
    width: 10px;
    border-radius: 10px;
    position: absolute;
    left: -25px;
    top: 40px;
    box-shadow: 190px 0 #1A1D2F;
  }
  .bolt::after {
    content: "";
    background: #1A1D2F;
    width: 25px;
    height: 10px;
    position: absolute;
    top: 10px;
    box-shadow: 175px 0 #1A1D2F;
  }
</style>

```
