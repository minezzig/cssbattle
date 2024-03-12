# [102. One Piece](https://cssbattle.dev/play/102)

![](https://cssbattle.dev/targets/102.png)

```HTML
<div class="head">
  <div class="eye"></div>
</div>
<div class="teeth"></div>
<div class="bone"></div>
<style>
  body {
    background: #000000;
    margin: 0;
    box-sizing: border-box;
  }
  .head {
    width: 150px;
    height: 100px;
    background: #FFFFFF;
    border-radius: 50px;
    position: relative;
    top: 110px;
    left: 125px;
  }
  .eye {
    position: absolute;
    height: 45px;
    width: 47px;
    background: #000000;
    left: 20px;
    bottom: 28px;
    border-radius: 40px 25px;
    -webkit-box-reflect: right 15px;
  }

  .teeth {
    width: 15px;
    height: 20px;
    background: #FFFFFF;
    position: absolute;
    bottom: 60px;
    left: 173px;
    box-shadow: 20px 0 #FFFFFF, 40px 0 #FFFFFF;
  }

  .bone {
    background: #FFFFFF;
    height: 25px;
    aspect-ratio: 1;
    border-radius: 50%;
    left: 95px;
    top: 95px;
    position: absolute;
    box-shadow: 10px -10px #FFFFFF,
                175px -10px #FFFFFF,
                185px 0 #FFFFFF,
                185px 105px #FFFFFF,
                175px 115px #FFFFFF,
                0 105px #FFFFFF,
                10px 115px #FFFFFF
  }
  .bone::after {
    content: "";
    background: #FFFFFF;
    height: 20px;
    aspect-ratio:1;
    position: absolute;
    left: 18px;
    top: 8px;
    box-shadow: 110px 110px #FFFFFF,
                 42px 175px #FFFFFF,
                -65px 65px #FFFFFF;
    rotate: -45deg;
  }
</style>

```
