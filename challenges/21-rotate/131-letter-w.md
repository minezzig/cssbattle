# [131. Letter W](https://cssbattle.dev/play/131)

![](https://cssbattle.dev/targets/131.png)

```HTML
<div class="you">
  <div class="rounded"></div>
</div>

<style>
  body {
    background: #E38F66;
    margin: 0;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
  }
  .you, .you::after {
    width: 60px;
    height: 115px;
    border: 30px solid #62306D;
    border-top: none;
    background: #E38F66;
    border-radius: 0 0 100px 100px;
    position: relative;
  }
  .you {
    left: -45px;
    bottom: -8px;
  }
  .you::after {
    content: "";
    position: absolute;
    border-color: #FFFBDA;
    z-index: -1;
    left: 60px;
  }
  .rounded{
    position: absolute;
    height: 30px;
    aspect-ratio: 1;
    background: #62306D;
    border-radius: 50%;
    left: -30px;
    top: -15px;
    box-shadow: 90px 0 0 #62306D,
                180px 0 0 #FFFBDA;
  }
</style>
```
