# [41. Fox Head](https://cssbattle.dev/play/41)

![](https://cssbattle.dev/targets/41.png)

```HTML
<div class="left"></div>
<div class="right"></div>
<div class="eyes"></div>
<div class="nose"></div>


<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .left {
    background: #FE5F55;
    height: 140px;
    width: 50px;
    position: absolute;
    left: 150px;
    top: 80px;
    border-radius: 0 40px 0 0;
  }

  .right {
    background: #FE5F55;
    height: 140px;
    width: 50px;
    position: absolute;
    right: 150px;
    top: 80px;
    border-radius: 40px 0 0 0;
  }

  .eyes {
    background: #293462;
    border-radius: 50%;
    height: 30px;
    width: 30px;
    position: absolute;
    top: 140px;
    left: 165px;
  }

  .eyes:after {
    content: "";
    background: #293462;
    border-radius: 50%;
    height: 30px;
    width: 30px;
    position: absolute;
	left: 40px;
  }

  .nose {
    background: #293462;
    border-radius: 50px;
    height: 80px;
    width: 100px;
    position: absolute;
    bottom: 40px;
    left: 100px;
  }

 .nose:after {
    content: "";
    background: #293462;
    border-radius: 50px;
    height: 80px;
    width: 100px;
    position: absolute;
	transform: translateX(100px);
  }
</style>

```
