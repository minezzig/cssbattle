# [51. Wear a Mask](https://cssbattle.dev/play/51)

![](https://cssbattle.dev/targets/51.png)

```HTML
<div class="strap"></div>
<div class="mask"></div>
<div class="circle"></div>
<div class="lines"></div>

<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .strap {
    height: 40px;
    width: 250px;
    border: 10px solid #FFF1C1;
    border-radius: 50px;
    position: absolute;
    top: 100px;
  }
  
  .mask {
    background: #FFF1C1;
    height: 100px;
    width: 150px;
    border-radius: 0 0 50px 50px;
    position: absolute;
    top: 100px;
  }
  
  .circle {
    background: #FE5F55;
    height: 40px;
    width: 40px;;
    border-radius: 50%;
    position: absolute;
    top: 140px;
    right: 145px;
  }
  
  .lines {
    background: #FE5F55;
    height: 10px;
    width: 40px;
    border-radius: 50px;
    position: absolute;
    top: 120px;
    left: 145px;
  }
  
  .lines:after {
    content: "";
    background: #FE5F55;
    height: 10px;
    width: 40px;
    border-radius: 50px;
    position: absolute;
	top: 20px;
  }
</style>

```
