# [62. Sunset](https://cssbattle.dev/play/62)

![](https://cssbattle.dev/targets/62.png)

```HTML
<div class="window">
<div class="moon"></div>
<div class="left"></div>
<div class="right"></div>
</div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .window {
    background-color: #F2AD43;
    height: 200px;
    width: 150px;
    border-radius: 75px 75px 20px 20px;
    overflow: hidden;
  }
  
  .moon {
    background-color: #FFF58F;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: relative;
	left: 45px;
    top: 90px; 
  }
  
  .left {
    background-color: #E08027;
    height: 200px;
    width: 200px;
    border-radius: 50%;
    position: relative;
	left: -50px;
    top: 40px;
	float: right;
  }
  
  .right {
    background-color: #824B20;
    height: 200px;
    width: 200px;
    border-radius: 50%;
    position: relative;
	left: 50px;
    top: 40px;
  }

</style>
```
