# [31. Equals](https://cssbattle.dev/play/31)

![](https://cssbattle.dev/targets/31.png)

```HTML
<div class="circle left"></div>
<div class="circle right"></div>
<style>
  body {
    background: #AA445F;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    width: 0;
    height: 0;
    border-radius: 50%;
    border: 100px solid #F7EC7D;
    border-top: 100px solid transparent;
    border-left: 100px solid transparent;
	position: absolute;
  }

  .left {
    transform: rotate(135deg);
	left: 75px;
  }

  .right {
 	transform: rotate(-45deg);
    border-bottom: 100px solid #E38F66;
    border-right: 100px solid #E38F66;
    right: 75px;
  }
</style>
```
