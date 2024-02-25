# [5. Acid Rain](https://cssbattle.dev/play/5)

![](https://cssbattle.dev/targets/5.png)

```html
<div></div>
<style>
  body {
    background-color: #0b2429;
    display: flex;
    margin: 0;
    box-sizing: border-box;
    align-items: center;
    justify-content: center;
  }
  div,
  ::before,
  ::after {
    background-color: #998235;
    height: 120px;
    aspect-ratio: 1;
    border-radius: 50% 0 50% 50%;
    position: relative;
  }
  div::before {
    content: "";
    position: absolute;
    background-color: #f3ac3c;
    translate: -60px 60px;
  }
  div::after {
    content: "";
    position: absolute;
    background-color: #f3ac3c;
    translate: 60px -60px;
    border-radius: 50%;
    z-index: -5;
  }
</style>
```
