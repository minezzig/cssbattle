# [93. Great Wall](https://cssbattle.dev/play/93)

![](https://cssbattle.dev/targets/93.png)

```HTML
<div class="main">
  <div class="sun"></div>
  <div class="bar"></div>
  <div class="ramp one"></div>
  <div class="ramp two"></div>
  <div class="ramp three"></div>
</div>
<style>
  body {
    background-color: #4F77FF;
    display: flex;
    align-items: center;
    justify-content: center;
    
  }
  .main {
    width: 200px;
    height: 200px;
    background: #191919;
    border-radius: 50%;
    position: relative;
    overflow: hidden;
  }
  .sun {
    height: 40px;
    width: 40px;
    border-radius: 50%;
    background-color: #F9E492;
    position: absolute;
    left: 40px;
    top: 40px;
  }
  
  .bar {
    background-color: #F9E492;
    height: 16px;
    width: 100px;
    position: absolute;
	bottom: 62px;
    box-shadow: 0 26px #F9E492,
                0 52px #F9E492,
                120px -13px #F9E492,
                120px 13px #F9E492,
                120px 39px #F9E492;
  }
  

  .ramp {
    height: 29px;
    width: 20px;
    background: #D6B73F;
    position: absolute;
    left: 100px;
    clip-path: polygon(0 13px, 100% 0, 100% 16px, 0 100%);
  }
  .one {
    bottom: 10px;
  }
  .two {
    bottom: 36px
  }
  .three {
    bottom: 62px
  }


</style>
```
