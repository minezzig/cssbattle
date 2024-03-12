# [105. Ryuk](https://cssbattle.dev/play/105)

![](https://cssbattle.dev/targets/105.png)

```HTML
<div class="forehead"></div>
<div class="left-eye-bg">
  <div class="left-eye"></div>
</div>
<div class="right-eye-bg">
  <div class="right-eye"></div>
</div>
<style>
  body {
    background-color: #BAC7CE;
    display: flex;
    align-items: center;
    justyify-content: center;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .forehead {
    width: 130px;
    height: 130px;
    background: #475862;
    transform: rotate(45deg);
    position: absolute;
    top: -65px;
    left: 135px
  }
  .left-eye-bg {
    background-color: #000000;
    position: relative;
    height: 120px;
    width: 120px;
    bottom: -40px;
    left: 30px;
    border-radius: 0px 50%;
    transform: rotate(-15deg);
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .left-eye {
    z-index: 3;
    height: 100px;
    width: 100px;
    box-shadow: inset 0 15px 0 #5A6042;
    transform: rotate(15deg);
    border-radius: 50%;
    background: radial-gradient(
      #4E2B24 0px, 
      #4E2B24 15px, 
      #000000 15px,
      #000000 20px,
      #868A64 20px,
      #868A64)
  }
   .right-eye-bg {
    background-color: #000000;
    position: relative;
    height: 120px;
    width: 120px;
    bottom: -40px;
     right: -130px;
    border-radius: 50% 0px;
    transform: rotate(15deg);
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .right-eye {
    z-index: 3;
    height: 100px;
    width: 100px;
    box-shadow: inset 0 15px 0 #5A6042;
    transform: rotate(-15deg);
    border-radius: 50%;
    background: radial-gradient(
      #4E2B24 0px, 
      #4E2B24 15px, 
      #000000 15px,
      #000000 20px,
      #868A64 20px,
      #868A64)
  }
</style>

```
