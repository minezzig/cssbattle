# [165. Pyramid](https://cssbattle.dev/play/165)

![](https://cssbattle.dev/targets/165.png)

```HTML
<div class="circle"></div>
<div class="triangle"></div>
<style>
  body {
    background: #F0CD48;
    display: grid;
    place-items: center;
  }
  .circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: #66284A;
    position: absolute;
    bottom: 30px;
    left: 50px;
    box-shadow: 200px 0 #66284A,
                100px -140px #66284A;
    z-index: -1;
  }
  .triangle {
    width: 0;
    aspect-ratio: 1;
    border-bottom: 140px solid #F0CD48;
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
  }
  .triangle::before {
    content: "";
    border-bottom: 100px solid #66284A;
    border-left: 70px solid transparent;
    border-right: 70px solid transparent;
    position: absolute;
    left: 50%;
    translate: -50%;
    bottom: 95px
  }
</style>
```
