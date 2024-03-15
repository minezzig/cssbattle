# [119. Pacman](https://cssbattle.dev/play/119)

![](https://cssbattle.dev/targets/119.png)

```HTML
<div class="man"><div class="mouth"></div></div>
<div class="balls"></div>
<div class="red">
  <div class="legs"></div>
</div>
<style>
  body {
    background: #000000;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .man {
    background-color: #E0E246;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: relative;
    left: -111px;
  }
  .mouth {
    width: 30px;
    height: 30px;
    background: black;
    transform-origin: bottom right;
    rotate: 135deg;
    position: absolute;
  }
  .balls, .balls::before, .balls::after {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #FFFFFF;
    position: absolute;
  }
  .balls::before {
    content: " ";
    translate: -30px;
  }
    .balls::after {
    content: " ";
    translate: 30px;
  }
  .red {
    position: absolute;
    right: 60px;
    top: 120px;
    height: 60px;
    width: 60px;
    background: #c74e4e;
    border-radius: 50px 50px 0 0
  }
  .legs, .legs::before, .legs::after {
    background: none;
    position: absolute;
    bottom: 0;
    left: -2;
    border-bottom: 12px solid black;
    border-left: 12px solid transparent;
    border-right: 12px solid transparent;
  }
  .legs::before {
    content: "";
    bottom: -12px;
    left: 7px;
  }
  .legs::after {
    content: "";
    left: 27px;
    bottom: -12px;
  }
</style>
```
