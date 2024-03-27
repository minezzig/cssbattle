# [176. Castlevania](https://cssbattle.dev/play/176)

![](https://cssbattle.dev/targets/176.png)

```HTML
<div class="container">
<div class="third-floor">
  <div class="tower-roof tr-left"></div>
  <div class="tower-roof tr-right"></div>
</div>
<div class="second-floor">
  <div class="tower">
    <div class="window"></div>
  </div>
  <div class="roof"></div>
  <div class="tower">
      <div class="window"></div>
  </div>
</div>
<div>
  <div class="house">
    <div class="door"></div>
  </div>
</div>
</div>
<style>
  body {
    margin:0;
    padding:0;
    box-sizing: border-box;
    background: #A6D6AE;
    display: flex;
    flex-direction: ;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
    .second-floor, .third-floor {
    display: flex;
    width: 100%;
    justify-content: space-between;
  }
  .tower-roof {
    border-bottom: 60px solid #3A0F09;
    border-left: 40px solid transparent;
    border-right: 40px solid transparent;
  }

  .tr-left {
    translate: -15px
  }
  .tr-right {
    translate: 15px
  }

  .tower {
    background-color: #3A0F09;
    height: 35px;
    width: 50px;
    position: relative;
  }
  .window {
    background-color: #BB9213;
    height: 25px;
    width: 20px;
    border-radius: 50px 50px 0 0;
    position: absolute;
    bottom: 0;
    left: 50%;
    translate: -50%;
  }
  .roof {
    border-bottom: 35px solid #3A0F09;
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
  }
  .house {
    background-color: #3A0F09;
    width: 200px;
    height: 85px;
    position: relative;
  }

  .door {
    background-color: #BB9213;
    height: 50px;
    width: 60px;
    border-radius: 50px 50px 0 0;
    position: absolute;
    bottom: 0;
    left: 50%;
    translate: -50%;
  }
</style>


```
