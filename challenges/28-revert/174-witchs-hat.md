# [174. Witch's Hat](https://cssbattle.dev/play/174)

![](https://cssbattle.dev/targets/174.png)

```HTML
<div class="hat"></div>
<style>
  body {
    background: #F4DCBF;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .hat {
    width: 0;
    aspect-ratio: 1;
    translate: 0 -10px;
    border-bottom: 180px solid #30383F;
    border-left: 53px solid transparent;
    border-right: 53px solid transparent;
  }
  .hat::before {
    content: "";
    width: 150px;
    height: 60px;
    border-radius: 50%;
    position: absolute;
    background: #30383F;
    top: 140px;
    left: -75px;
    box-shadow: inset 0 -25px #30383F,
                inset 0 -35px #556D7F;
  }
  .hat::after {
    content: "";
    background: #FBD038;
    width: 30px;
    height: 20px;
    border-radius: 5px;
    position: absolute;
    bottom: -180px;
    left: -15px;

  }
</style>

```
