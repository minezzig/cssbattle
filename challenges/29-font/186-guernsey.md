# [186. Guernsey](https://cssbattle.dev/play/186)

![](https://cssbattle.dev/targets/186.png)

```HTML
<div class="red">
  <div class="cross"></div>
</div>
<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: #FFFFFF;
  }

  .red {
    background-color: #E8112D;
    height: 100%;
    width: 100%;
    clip-path: polygon(
      160px 0,
      240px 0,
      240px 110px,
      400px 110px,
      400px 190px,
      240px 190px,
      240px 300px,
      160px 300px,
      160px 190px,
      0 190px,
      0 110px,
      160px 110px);
  }

  .cross {
    width: 100%;
    height: 100%;
    background-color: #F9DD16;
    z-index: 5;
    clip-path: polygon(
      180px 35px,
      220px 35px,
      210px 50px,
      210px 140px,
      300px 140px,
      315px 130px,
      315px 170px,
      300px 160px,
      210px 160px,
      210px 250px,
      220px 265px,
      180px 265px,
      190px 250px,
      190px 160px,
      100px 160px,
      85px 170px,
      85px 130px,
      100px 140px,
      190px 140px,
      190px 50px,
      180px 35px

    );
    position: absolute;
    left: 50%;
    top: 50%;
    translate: -50% -50%;
  }
</style>


```
