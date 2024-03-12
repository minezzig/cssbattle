# [103. Super Saiyan](https://cssbattle.dev/play/103)

![](https://cssbattle.dev/targets/103.png)

```HTML
<div>
<div class="hair"></div>
<div class="face">
  <div class="mouth"></div>
</div>
</div>
<style>
  body {
    background: #161616;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .mouth {
    position: absolute;
    background-image: linear-gradient(to top, #161616, #161616 50%, transparent 50%);
    height: 20px;
    aspect-ratio: 1;
    border-radius: 50%;
    bottom: 10px;
    left: 30px
  }
  .hair {
    height: 85px;
    width: 33px;
    background: #EBAE11;
    position: absolute;
    z-index: 1;
    top: 85px;
    left: 185px;
    border-radius: 50%;
  }
  .hair::before, .hair::after {
    content: "";
    background-image: linear-gradient(#EBAE11, #EBAE11 50%, transparent 50%);
    height: 60px;
    aspect-ratio: 1;
    position: absolute;
    border-radius: 50%;
    bottom: -1px;
  }

  .hair::before {
    rotate: -123deg;
    left: -30px;
  }
  .hair::after {
    rotate: 118deg;
    right: -30px;
  }
  .face {
    position: absolute;
    top: 35px;
    width: 80px;
    height: 60px;
    background: #dd6b4d;
    border-radius: 0 0 40px 40px;
    background-image: linear-gradient(to right, #FFFFFF, #FFFFFF 50%, #FFDEB9 50%);
    position: relative;
  }
  .face::before, .face::after {
    content: "";
    background: linear-gradient(transparent, transparent 50%, #EBAE11 50%);
    width: 60px;
    border-radius: 50%;
    aspect-ratio: 1;
    position: absolute;
    z-index: -1;
    bottom: 25px;
  }
  .face::before {
    left: -20px;
    rotate: 17deg;
  }
   .face::after {
    right: -20px;
    rotate: -17deg;
  }

</style>
```
