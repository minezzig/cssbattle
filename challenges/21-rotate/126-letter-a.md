# [126. Letter A](https://cssbattle.dev/play/126)

![](https://cssbattle.dev/targets/126.png)

```HTML
<div class="A"></div>
<div class="B"></div>

<style>
  body {
    background-color: #62306D;
    margin: 0;
  }
  .A, .A::before, .A::after {
    width: 43px;
    height: 140px;
    position: absolute;
    transform-origin: bottom right;
  }
    .A {
    background: #C5B732;

    transform: skew(20deg);
    right: 123px;
    bottom: 80px;
  }
  .A::after {
    content: "";
    background: #FEF9CA;
    transform: skew(-36deg);
    right: 111px;
  }
    .B, .B::before, .B::after {
    width: 53px;
    height: 50px;
    position: absolute;
    transform-origin: bottom right;
  }
    .B {
    background: #AA445F;

    transform: skew(40deg);
    right: 129px;
    bottom: 80px;
  }
  .B::after {
    content: "";
    background: #E38F66;
    transform: skew(-60deg);
    left: -92;
  }

</style>
```
