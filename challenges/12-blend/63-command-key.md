# [63. Command Key](https://cssbattle.dev/play/63)

![](https://cssbattle.dev/targets/63.png)

```HTML
<div class="top-left"></div>i
<div class="top-right"></div>
<div class="bottom-left"></div>
<div class="bottom-right"></div>
<div class="center"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .center {
    background: #191919;
    width: 50px;
    height: 50px;
    border: 10px solid #5DBCF9;
    position: absolute;
    left: 166px;
    top: 114px;
  }

  .top-left {
    background: #191919;
    width: 50px;
    height: 50px;
    border: 10px solid #5DBCF9;
    border-radius: 50% 50% 0 50%;
    position: absolute;
    left: 106px;
    top: 54px
  }
  
  .top-right {
    background: #191919;
    width: 50px;
    height: 50px;
    border: 10px solid #5DBCF9;
    border-radius: 50% 50% 50% 0;
    position: absolute;
    right: 104px;
    top: 54px
  }
  
  .bottom-left {
    background: #191919;
    width: 50px;
    height: 50px;
    border: 10px solid #5DBCF9;
    border-radius: 50% 0 50% 50%;
    position: absolute;
    left: 106px;
    bottom: 56px
  }
  
  .bottom-right {
    background: #191919;
    width: 50px;
    height: 50px;
    border: 10px solid #5DBCF9;
    border-radius: 0 50% 50% 50%;
    position: absolute;
    right: 104px;
    bottom: 56px
  }
</style>

```
