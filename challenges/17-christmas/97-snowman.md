# [97. Snowman](https://cssbattle.dev/play/97)

![](https://cssbattle.dev/targets/97.png)

```HTML
<div class="hat">
  <div class="stripe"></div>
  <div class="brim"></div>
</div>

<div class="head">
  <div class="eye1"></div>
  <div class="eye2"></div>
</div>
<div class="scarf"></div>
<div class="body"></div>
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #AC474B;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .hat {
    background: linear-gradient(to bottom,
  	  black,
      black 15px,
      white 15px,
      white 25px,
      black 20px,
      black
);
    height: 40px;
    width: 40px;
    position: absolute;
    top: 55px;
  }
  
  .brim {
    background-color: #0E1F2B;
    width: 60px;
    height: 5px;
    position: absolute;
    z-index: 4;
    top: 40px;
    left: -10px;
    
  }
  
  .eye1 {
	background-color: #0E1F2B;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    left: 15px;
    top: 18px;
  }
  .eye2 {
	background-color: #0E1F2B;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    right: 15px;
    top: 18px;
  }
  .head {
    position: absolute;
    background-color: #FFFFFF;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    transform: translateY(-25px)
  }
  .scarf {
    position: absolute;
    background-color: #FFA63F;
    height: 10px;
    width: 60px;
    border: 4px solid #AC474B ;

    border-radius: 15px;
    z-index: 2;
    transform: translateY(-2px);
  }
  .body {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #FFFFFF;
    border-radius: 50%;
    transform: translateY(45px);
  }
</style>
```
