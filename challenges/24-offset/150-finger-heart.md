# [150. Finger Heart](https://cssbattle.dev/play/150)

![](https://cssbattle.dev/targets/150.png)

```HTML
<div class="square">
  <div class="bulb"></div>
</div>

<style>
  body {
    background: #4F77FF;
    margin: 0;
  }
  .square {
    width: 150px;
    height: 150px;
    background: #1038BF;
    position: relative;
  }
  .bulb, ::after {
    background: #1038BF;
    height: 50px;
    width: 50px;
    position: absolute;
    border-radius: 0 0 50% 50%;
  }
  .bulb {
    right: 0;
    bottom: -50px;
  }
  .bulb::after {
    content: "";
    rotate: -90deg;
    right: -50px;
    bottom: 50px;
  }
</style>

```
