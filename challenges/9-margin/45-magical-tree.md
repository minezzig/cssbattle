# [45. Magical Tree](https://cssbattle.dev/play/45)

![](https://cssbattle.dev/targets/45.png)

```HTML
<div class="main"></div>
<div class="inner"></div>
<div class="vertical"></div>
<div class="horizontal"></div>
<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .main {
    background: #1A4341;
    height: 180px;
    width: 210px;
    border: 30px solid #F3AC3C;
    position: absolute;
    top: -30px;
  }
  
  .inner {
    background: #1A4341;
    height: 120px;
    width: 90px;
    border: 30px solid #998235;
    position: absolute;
    top: -30px;
  }
  
  .vertical {
    background: #F3AC3C;
    width: 30px;
    height: 300px;
    position: absolute;
  }
  
  .horizontal {
    background: #998235;
    height: 30px;
    width: 270px;
    position: absolute;
    bottom: 30px;
    z-index: -1;
    
  }
</style>

```
