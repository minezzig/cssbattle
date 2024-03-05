# [43. Wrench](https://cssbattle.dev/play/43)

![](https://cssbattle.dev/targets/43.png)

```HTML
<div class="container">
  <div class="left"></div>
  <div class="right"></div>
</div>

<style>
  body {
    background: #6592CF;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .container {
    height: 240px;
    width: 110px;
    overflow: hidden;
  }
  .left {
    background: #6592CF;
    height: 180px;
    width: 180px;
    border: 30px solid #243D83;
    border-radius: 70px;
	  position: relative;
    left: -170px;
  }
  
  .right {
    background: #6592CF;
    height: 180px;
    width: 180px;
    border: 30px solid #243D83;
    border-radius: 70px;
	  position: relative;
    left: 40px;
    bottom: 240px;
  }
</style>
```
