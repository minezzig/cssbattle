# [19. Cube](https://cssbattle.dev/play/19)

![](https://cssbattle.dev/targets/19.png)

```HTML
<div class="front"></div>
<div class="left"></div>
<div class="right"></div>
<style>
  body {
    margin: 0;
    background-color: #0B2429;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .front {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    transform: rotate(45deg);
    position: absolute;
    bottom: 65px;
  }

  .left {
    background: #998235;
    height: 70px;
    width: 70px;
    position: absolute;
    top: 80px;
    left: 130px;
    transform: rotate(90deg)
      		   skew(45deg);
  }

  .right {
    background: #1A4341;
    height: 70px;
    width: 70px;
    position: absolute;
    top: 80px;
    right: 130px;
    transform: rotate(90deg)
      		   skew(-45deg);
  }
</style>

```
