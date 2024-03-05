# [49. Stay at Home](https://cssbattle.dev/play/49)

![](https://cssbattle.dev/targets/49.png)

```HTML
<div class="house"></div>
<div class="roof"></div>
<div class="door"></div>
<div class="light"></div>

<style>
  body {
    background: #6592CF;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .house {
    background: #243D83;
    height: 120px;
    width: 150px;
    border-radius: 10px;
    position: absolute;
    bottom: 50px;
  }
  
  .roof {
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
    border-bottom: 100px solid #243D83;
    position: absolute;
    top: 50px;
  }
  
  .door {
    background: #EEB850;
    height: 50px;
    width: 50px;
    border-radius: 10px 10px 0 0;
    position: absolute;
    bottom: 50px;
  }
  
  .light {
    background: #EEB850;
    height: 10px;
    width: 100px;
    border-radius: 10px;
    position: absolute;

  }
</style>

```
