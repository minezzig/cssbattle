# [11. Eyes of Sauron](https://cssbattle.dev/play/11)

![](https://cssbattle.dev/targets/11.png)

```html
<div class="left-container">
  <div class="left-ring">
    <div class="left-inner-ring"></div>
  </div>
</div>
<div class="ring">
  <div class="inner-ring">
    <div class="dot"></div>
  </div>
</div>
<div class="right-container">
  <div class="right-ring">
    <div class="right-inner-ring"></div>
  </div>
</div>

<style>
  body {
    background-color: #191210;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .left-container {
    height: 50px;
    width: 100px;
    position: absolute;
    left: 50px;
    top: 150;
    overflow: hidden;
  }
  .left-ring {
    border-radius: 50%;
    height: 100px;
    width: 100px;
    background-color: #eca03d;
    position: absolute;
    bottom: 0px;
  }

  .left-inner-ring {
    border-radius: 50%;
    height: 60px;
    width: 60px;
    background-color: #191210;
    position: absolute;
    bottom: 20px;
    left: 20px;
  }

  .ring {
    background-color: #eca03d;
    border-radius: 50%;
    height: 140px;
    width: 140px;
    position: absolute;
  }

  .inner-ring {
    background-color: #191210;
    border-radius: 50%;
    height: 100px;
    width: 100px;
    position: relative;
    top: 20px;
    left: 20px;
  }

  .dot {
    background-color: #84271c;
    border-radius: 50%;
    height: 50px;
    width: 50px;
    position: relative;
    top: 25px;
    left: 25px;
  }

  .right-container {
    height: 50px;
    width: 100px;
    position: absolute;
    right: 50px;
    top: 100px;
    overflow: hidden;
  }
  .right-ring {
    border-radius: 50%;
    height: 100px;
    width: 100px;
    background-color: #eca03d;
    transform: rotateX(180deg);
  }

  .right-inner-ring {
    border-radius: 50%;
    height: 60px;
    width: 60px;
    background-color: #191210;
    position: absolute;
    bottom: 20px;
    left: 20px;
  }
</style>
```
