# [14. Web Maker Logo](https://cssbattle.dev/play/14)

![](https://cssbattle.dev/targets/14.png)

```HTML
<div class="triangle1"></div>
<div class="triangle2"></div>

<style>
  body {
    background-color: #F2F2B6;
    margin: 0;
    display: flex;
    position: absolute;
  }

  .triangle1 {
    position: relative;
    height: 0;
    width: 0;
    border-top: 130px solid #FF6D00;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent;
    top: 85px;
    left: 60px;
  }

  .triangle1:after {
    content: "";
    position: relative;
    height: 0;
    width: 0;
    border-top: 130px solid #FD4602;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent;
    left: -55px;
    z-index: -1;;
  }

  .triangle2 {
    height: 0;
    width: 0;
    border-bottom: 130px solid #FD4602;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    position: absolute;
    top: 85px;
    left: 170px;
  }

    .triangle2:after {
    content: "";
    height: 0;
    width: 0;
    border-bottom: 130px solid #FF6D00;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    position: absolute;
    left: -55px;
    z-index: -1;
  }
</style>
```
