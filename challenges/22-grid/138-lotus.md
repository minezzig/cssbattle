# [138. Lotus](https://cssbattle.dev/play/138)

![](https://cssbattle.dev/targets/138.png)

```HTML

<div class="lotus"></div>

<style>
  body {
    margin: 0;
    background: #926927;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .lotus, .lotus::before, .lotus::after {
    width: 100px;
    height: 100px;
    background: #FFFFFF;
    border-radius: 95% 0;
  }
  .lotus {
    transform: rotate(-45deg);
    position: absolute;
  }
  .lotus::before {
    content: "";
    background: #6D480A;
    transform-origin: bottom left;
    transform: rotate(-45deg);
    position: absolute;
    z-index: -3;
  }
    .lotus::after {
    content: "";
    background: #6D480A;
    transform-origin: bottom left;
    transform: rotate(45deg);
    position: absolute;
    z-index: -3;
  }

</style>

```
