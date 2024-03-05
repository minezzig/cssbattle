# [47. Corona Virus](https://cssbattle.dev/play/47)

![](https://cssbattle.dev/targets/47.png)

```HTML
<div class="rods"></div>
<div class="atom"></div>
<div class="dots"></div>

<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .atom {
    background: #F3AC3C;
    height: 100px;
    width: 100px;
    border-radius: 50%;
  }

  .rods {
    position: absolute;
    background: #F3AC3C;
    height: 180px;
    width: 10px;
    border-radius: 50px;
    top: 50px;
  }

  .rods:before {
    content: "";
    position: absolute;
    background: #F3AC3C;
    height: 180px;
    width: 10px;
    border-radius: 50px;
    transform: rotate(60deg)
      		   translate(8px,-5px);
  }

  .rods:after {
    content: "";
    position: absolute;
    background: #F3AC3C;
    height: 180px;
    width: 10px;
    border-radius: 50px;
    transform: rotate(-60deg)
      		   translate(-8px,15px);
  }

  .dots {
    background: #998235;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
    bottom: 115px;
  }

  .dots:before {
    content: "";
    background: #998235;
    height: 30px;
    width: 30px;
    border-radius: 50%;
    position: absolute;
    bottom: 35px;
    right: 10px;
  }

  .dots:after {
    content: "";
    background: #998235;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    bottom: 55px;
    left: 30px;
  }
</style>

```
