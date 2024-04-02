# [185. South Korea](https://cssbattle.dev/play/185)

![](https://cssbattle.dev/targets/185.png)

```HTML
<div class="bars topLeft">
  <div></div>
  <div></div>
  <div></div>
</div>
<div class="bars bottomLeft">
  <div></div>
  <div></div>
  <div></div>
</div>
<div class="bars topRight">
  <div></div>
  <div></div>
  <div></div>
</div>
<div class="bars bottomRight">
  <div></div>
  <div></div>
  <div></div>
</div>

<div class="circle">
  <div class="yinyang"></div>
</div>


<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: #FFFFFF;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .bars {
    position: absolute;
  }
  .topleft {
    rotate: -60deg;
    top: 70px;
    left: 69px;
  }
  .bottomLeft {
    rotate: 60deg;
    bottom: 70px;
    left: 69px;
  }
  .bottomLeft.bars div:nth-child(2){
  background: linear-gradient(to right, black 28px, white 28px 33px, black 33px 60px);
  }
    .topRight {
    rotate: 60deg;
    top: 70px;
    right: 69px;
  }
    .topRight.bars div:nth-child(odd){
  background: linear-gradient(to right, black 28px, white 28px 33px, black 33px 60px);
  }
    .bottomRight {
    rotate: -60deg;
    bottom: 70px;
    right: 69px;
  }
      .bottomRight.bars div{
  background: linear-gradient(to right, black 28px, white 28px 33px, black 33px 60px);
  }
  
  .bars div {
    height: 10px;
    width: 60px;
    background-color: black;
    margin: 6px;
  }
  .circle {
    height: 120px;
    width: 120px;
    border-radius: 50%;
    background: linear-gradient(to bottom, #CD2E3A 50%, #0047A0 50%);
    position: relative;
  }

  .yinyang, .yinyang::after{
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: #CD2E3A;
  }

  .yinyang {
    top: 25%;
    position: relative;
  }

  .yinyang::after {
    content: "";
    background-color: #0047A0;
    left: 0;
    position: absolute;
    left: 100%;
  }
</style>

```
