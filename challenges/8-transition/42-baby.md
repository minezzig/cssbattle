# [42. Baby](https://cssbattle.dev/play/42)

![](https://cssbattle.dev/targets/42.png)

```HTML
<div class="mushroom">
  <div class="hair"></div>
</div>
<div class="eyes"></div>
<div class="mouth"></div>

<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .mushroom {
    background: #FE5F55;
    height: 200px;
    width: 200px;
    border-radius: 50% 50% 50px 50px;
    overflow: hidden;
  }

  .hair {
    background: #FFF1C1;
    border-radius: 50%;
    height: 96px;
    width: 96px;
    position: relative;
    top: -46px;
    left: 3px;
  }

  .hair:after {
    content: "";
    background: #FFF1C1;
    border-radius: 50%;
    height: 96px;
    width: 96px;
    position: absolute;
    left: 96px;

  }

  .eyes {
    background: #FFF1C1;
    border-radius: 50%;
    height: 60px;
    width: 60px;
    position: absolute;
    top: 140px;
    left: 120px;
  }

  .eyes:after {
    content: "";
    background: #FFF1C1;
    border-radius: 50%;
    height: 60px;
    width: 60px;
    position: absolute;
	  left: 100px;
  }

  .mouth {
    background: #FFF1C1;
    border-radius: 50px;
    height: 10px;
    width: 40px;
    position: absolute;
    bottom: 70px;
    left: 2-0px;
  }
</style>
```
