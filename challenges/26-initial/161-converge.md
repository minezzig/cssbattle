# [161. Converge](https://cssbattle.dev/play/161)

![](https://cssbattle.dev/targets/161.png)

```HTML
<div></div>
<style>
  body {
    background: #E3516E;
    display: grid;
    place-content: center;
  }
  div {
    width: 184px;
    height: 183px;
    background: #FADE8B;
    position: relative;
  }
  div::before, div::after {
    content: "";
    position: absolute;
    width: 30px;
    height: 300px;
    background: #E3516E;
    bottom: 0;
    transform-origin: bottom;
  }
  div::before {
    transform: translate(-50%) rotate(45deg);
  }
  div::after {
    right: 0;
    transform: translate(50%) rotate(-45deg);
  }
</style>
```
