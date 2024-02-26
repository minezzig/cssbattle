# [38. Not Simply Square](https://cssbattle.dev/play/38)

![](https://cssbattle.dev/targets/38.png)

```HTML
<div class="square"></div>
<div class="red-square"></div>
<div class="border-square"></div>

<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .square {
    background: #FFF1C1;
    height: 200px;
    width: 200px;
    position: absolute;
    top: 0;
    left: 0;
  }

  .red-square {
    background: #FE5F55;
    height: 300px;
    width: 300px;
    position: absolute;
    left: 0;
    z-index: -1;
  }

  .border-square {
    background: #293462;
    height: 100px;
    width: 100px;
    position: absolute;
    right: 100px;
    bottom: -50;
    border: 50px solid #A64942;
    border-right: none;
    z-index: -1;
  }

</style>

```
