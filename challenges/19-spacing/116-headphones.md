# [116. Headphones](https://cssbattle.dev/play/116)

![](https://cssbattle.dev/targets/116.png)

```HTML
<div class="handle"></div>
<div class="phone left"></div>
<div class="phone right"></div>
<style>
  body {
    background: #293D7E;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .handle {
    width: 130px;
    height: 125px;
    background: transparent;
    border: 20px solid #6E91CA;
    border-bottom: transparent;
    border-radius: 100px 100px 0 0;
    position: absolute;
    top: 45px;
  }
  .phone {
    background: #6E91CA;
    width: 60px;
    height: 80px;
    position: absolute;    
    bottom: 55px;
  }
  .left {
    left: 115px;
    border-radius: 0 30px 50px 50px
  }
    .right {
    right: 115px;
    border-radius: 30px 0 50px 50px
  }
</style>
```
