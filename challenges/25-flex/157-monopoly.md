# [157. Monopoly](https://cssbattle.dev/play/157)

![](https://cssbattle.dev/targets/157.png)

```HTML
 <div class="hat-container"> 
   <div class="hat"></div>
   <div class="brim"></div>
 </div>
<div class="eyes">
  <div class="left-eye"></div>
  <div class="right-eye"></div>
</div>
  <div class="stache left"></div>
<div class="stache right"></div>

<style>
  body {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: #E38F66;
    margin: 0;
    box-sizing: border-box;
    padding: 0;
  }
  .hat-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: absolute;
    top: 40px;
  }
  .hat {
    background: #FFFBDA;
    height: 90px;
    width: 120px;
    border-radius: 70px 70px 0 0;
  }
  .brim {
    width: 180px;
    height: 20px;
    background: #FFFBDA;
    border-radius: 50px;
  }
  .eyes {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 150px;
    position: absolute;
    top: 162px;
    left: 130px;
  }
  .left-eye {
    height: 20px;
    width: 20px;
    border-radius: 50%;
    background: #FFFBDA;
    margin-right: 30px;
  }
  .right-eye {
    background: #E38F66;
    border-radius: 50%;
    height: 20px;
    width: 20px;
    border: 10px solid #FFFBDA;
  }
  .stache {
    background: #FFFBDA;
    height: 40px;
    width: 40px; 
    rotate: 45deg;
    position: absolute;
    bottom: 40px;
  }
  .left {
    border-radius: 50% 50% 50% 0;
    translate: -25px;
  }
  .right {
    border-radius: 50% 0 50% 50%;
    translate: 25px;
  }
</style>

```
