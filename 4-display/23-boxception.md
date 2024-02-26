# [23. Boxception](https://cssbattle.dev/play/23)

![](https://cssbattle.dev/targets/23.png)

```HTML
<div class="small"></div>
<div class="medium"></div>
<div class="big"></div>

<style>
  body {
    background-color: #F3AC3C;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .big {
    background: #1A4341;
    height: 200px;
    width: 200px;
  }

  .medium {
    position: absolute;
    background: #998235;
    height: 100px;
    width: 100px;
    left: 100px;
    bottom: 50px;
  }

  .small {
    position: absolute;
    background: #F3AC3C;
    height: 50px;
    width: 50px;
    left: 150px;
    bottom: 50px;
    z-index: 5;
  }
</style>
```
