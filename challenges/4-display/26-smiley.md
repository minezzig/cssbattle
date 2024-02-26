# [26. Smiley](https://cssbattle.dev/play/26)

![](https://cssbattle.dev/targets/26.png)

```HTML
<div class="left-eye"></div>
<div class="right-eye"></div>
<div class="smile"></div>
<style>
  body {
    background: #6592CF;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .left-eye {
    border-radius: 50%;
    height: 80px;
    width: 80px;
    background: #6592CF;
    border: 20px solid #060F55;
    border-left: 20px solid transparent;
    border-bottom: 20px solid transparent;
    transform: rotate(-45deg);
    position: absolute;
    top: 40px;
    left: 40px;
  }

    .right-eye {
    border-radius: 50%;
    height: 80px;
    width: 80px;
    background: #6592CF;
    border: 20px solid #060F55;
    border-left: 20px solid transparent;
    border-bottom: 20px solid transparent;
    transform: rotate(-45deg);
    position: absolute;
    top: 40px;
    right: 40px;
  }

    .smile {
    border-radius: 50%;
    height: 80px;
    width: 80px;
    background: #6592CF;
    border: 20px solid #060F55;
    border-right: 20px solid transparent;
    border-top: 20px solid transparent;
    transform: rotate(-45deg);
    position: absolute;
    bottom: 40px;
    right: 140px;
  }

</style>
```
