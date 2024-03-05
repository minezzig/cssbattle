# [60. Evil Triangles](https://cssbattle.dev/play/60)

![](https://cssbattle.dev/targets/60.png)

```HTML
<div class="rectangle"></div>
<div class="base-triangle"></div>
<div class="blackout-triangle"></div>
<div class="top-triangle"></div>





<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .rectangle {
    background: #4F77FF;
    height: 150px;
    width: 200px;
  }

  .base-triangle {
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
    border-bottom: 50px solid #191919;
    position: absolute;
    bottom: 75px;
  }

  .base-triangle:before {
    content: "";
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
    border-bottom: 50px solid #191919;
    position: absolute;
    right: 50px;
  }

  .base-triangle:after {
    content: "";
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
    border-bottom: 50px solid #191919;
    position: absolute;
    left: 50px;
  }

  .blackout-triangle {
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
    border-top: 50px solid #191919;
    position: absolute;
    bottom: 125px;
    left: 100px;
  }

  .blackout-triangle:after {
    content: "";
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
    border-top: 50px solid #191919;
    position: absolute;
	bottom: 0;
    left: 50px;
  }

  .top-triangle {
    border-left: 50px solid #191919;
    border-right: 50px solid #191919;
    border-top: 50px solid #4F77FF;
    position: absolute;
	top: 75px;
    left: 100px;
  }

  .top-triangle:after {
    content: "";
    border-left: 50px solid #191919;
    border-right: 50px solid #191919;
    border-top: 50px solid #4F77FF;
    position: absolute;
	top: -50px;
    left: 50px;
  }
</style>
```
