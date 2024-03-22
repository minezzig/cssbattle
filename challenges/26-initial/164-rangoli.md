# [164. Rangoli](https://cssbattle.dev/play/164)

![](https://cssbattle.dev/targets/164.png)

```HTML
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="four"></div>
<style>

  body {
    background: #66284A;
    display: grid;
    place-content: center;
  }
  div {
    position: absolute;
    width: 60px;
    aspect-ratio: 1;
    border-radius: 50%;
    border: 20px solid var(--color);
    border-left: 20px solid transparent;
  }
  .one {
    --color: #F0CD48;
    top: 40px;
    left: 150px;
    rotate: -45deg;
  }
  .two {
    --color: #D669EC;
    top: 100px;
    right: 90px;
    rotate: 45deg;
  }
  .three {
    --color: #FDFBF8;
    bottom: 40px;
    left: 150px;
    rotate: 135deg;
  }
  .four {
    --color: #D86F45;
    top: 100px;
    left: 90px;
    rotate: -135deg;
  }

</style>
```
