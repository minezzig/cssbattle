# [173. Hockey Mask](https://cssbattle.dev/play/173)

![](https://cssbattle.dev/targets/173.png)

```HTML
<div class="face"></div>
<style>
  body {
    background: #A5B5B4;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .face {
    width: 150px;
    height: 180px;
    background: #FFFFFF;
    border-radius: 50%;
    position: relative;
  }
  .face::before {
    content: "";
    position: absolute;
    background: #000000;
    height: 30px;
    aspect-ratio: 1;
    border-radius: 50%;
    top: 50px;
    left: 25px;
    box-shadow: 70px 0 0 #000000,
                20px -40px 0 -10px #000000,
                50px -40px 0 -10px #000000,
                35px -20px 0 -10px #000000,
                20px 40px 0 -10px #000000,
                20px 60px 0 -10px #000000,
                20px 80px 0 -10px #000000,
                50px 40px 0 -10px #000000,
                50px 60px 0 -10px #000000,
                50px 80px 0 -10px #000000;
  }

</style>

```
