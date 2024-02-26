# [20. Ticket](https://cssbattle.dev/play/20)

![](https://cssbattle.dev/targets/20.png)

```HTML
<div class="ticket">
  <div class="cutout tl"></div>
  <div class="cutout tr"></div>
  <div class="cutout tm"></div>
  <div class="cutout bm"></div>
  <div class="cutout bl"></div>
  <div class="cutout br"></div>
</div>
<style>
  body {
    background-color: #62306D;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .ticket {
    width: 200px;
    height: 100px;
    background-image: linear-gradient(to right, #F7EC7D, #F7EC7D 140px, #E38F66 140px);
    position: relative;
  }

  .cutout {
    height: 40px;
    aspect-ratio: 1;
    background-color: #62306D;
    border-radius: 50%;
    position: absolute;
  }

  .tl {
    top: -20px;
    left: -20px;
  }
  .tr {
    top: -20px;
    right: -20px;
  }
  .bl {
    bottom: -20px;
    left: -20px;
  }
  .br {
    bottom: -20px;
    right: -20px
  }
  .tm {
    top: -10px;
    left: 130px;
    height: 20px;
  }
  .bm {
    bottom: -10px;
    left: 130px;
    height: 20px;
  }
</style>

```
