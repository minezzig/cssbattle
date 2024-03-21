# [158. Clubs](https://cssbattle.dev/play/158)

![](https://cssbattle.dev/targets/158.png)

```HTML
<div class="clover"></div>
<div class="stem"></div>
<div class="cutout"></div>
<style>
  body {
    background: #4F77FF;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .clover, ::before, ::after {
    background: #1038BF;
    height: 100px;
    width: 100px;
    border-radius: 50%;
  }
  .clover {
    translate: 0 -50px;
  }
  .clover::before {
    content: "";
    position: absolute;
    top: 70px;
    right: 45px;
  }
    .clover::after {
    content: "";
    position: absolute;
    top: 70px;
    left: 45px;
  }

  .stem {
    background: #1038BF;
    height: 100px;
    width: 50px;
    position: absolute;
    bottom: 50px;
    z-index: -2;
  }
  .cutout, .cutout::after {
    background: #4F77FF;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
  }

  .cutout {
    bottom: 40px;
    left: 95px;
    z-index: -2;
  }

  .cutout::after {
    content: "";
    right: -110px;
  }
</style>
```
