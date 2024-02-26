# [27. Lockup](https://cssbattle.dev/play/27)

![](https://cssbattle.dev/targets/27.png)

```HTML
<div class="outter"></div>
<div class="inner"></div>
<style>
  body {
    background-color: #E38F66;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0;
  }

  .outter {
    background: #AA445F;
    height: 200px;
    width: 200px;
    border-radius: 50%;
  }

  .inner {
    background: #AA445F;
    height: 80px;
    width: 80px;
    border-radius: 50%;
    position: absolute;
    border: 30px solid #F7EC7D;
    border-top: 30px solid transparent;
    border-bottom: 30px solid transparent;
    transform: rotate(-45deg);
  }
</style>
```
