# [75. Hippo](https://cssbattle.dev/play/75)

![](https://cssbattle.dev/targets/75.png)

```HTML
<div class="head">
  <p class="eyes"></p>
</div>
<div class="snout">
  <p class="nostril"></p>
</div>
<div class="ear-left"></div>
<div class="ear-right"></div>

<style>
  body {
    background:#191919;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .head {
    background: #FE5F55;
    height: 100px;
    width: 130px;
    border-radius: 60px 60px 0 0;
    position: absolute;
    top: 75px;
  }
  
  .snout {
    background: #A64942;
    height: 100px;
    width: 150px;
    border-radius: 80px 80px 65px 65px;
    position: absolute;
	top: 145px;
  }
  
  .nostril::before,::after {
    background: #000000;
    height: 30px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
  }
  
  .nostril::before {
    content: "";
    left: 25px;
    bottom: 50px;
    transform: rotate(45deg);
  }
  
  .nostril::after {
    content: "";
    right: 25px;
    bottom: 50px;
    transform: rotate(-45deg);
  }

  .eyes {
    background: #000000;
    height: 10px;
    width: 10px;
    position: absolute;
    border-radius: 50%;
    top: 34px;
    left: 25px;
    -webkit-box-reflect: right 60px;
  }

  .ear-left {
    background: #191919;
    border: 5px solid #FE5F55;
    height: 20px;
    width: 10px;
    position: absolute;
    top: 70px;
    left: 150px;
    border-radius: 50%; 
   	transform: rotate(-45deg);
    z-index: -1;
  }
  
  .ear-right {
    background: #191919;
    border: 5px solid #FE5F55;
    height: 20px;
    width: 10px;
    position: absolute;
    top: 70px;
    right: 150px;
    border-radius: 50%; 
   	transform: rotate(45deg);
    z-index: -1;
  }
</style>
```
