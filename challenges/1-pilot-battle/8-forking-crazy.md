# [8. Forking Crazy](https://cssbattle.dev/play/8)

![](https://cssbattle.dev/targets/8.png)

```html
<div class="fork">
  <div class="caps-div">
    <div class="caps"></div>
    <div class="caps"></div>
    <div class="caps"></div>
    <div class="caps"></div>
  </div>
  <div class="divits"></div>
  <div class="divits"></div>
  <div class="divits"></div>
</div>
<div class="stem"></div>
<style>
  body {
    margin: 0;
    background-color: #6592cf;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .fork {
    background-color: #060f55;
    height: 190px;
    width: 120px;
    border-radius: 0 0 70px 70px;
    position: absolute;
    top: 60px;
    display: flex;
    justify-content: space-around;
    padding: 0 10;
  }

  .stem {
    background-color: #060f55;
    height: 100px;
    width: 20px;
    position: relative;
    top: 100;
  }

  .divits {
    background-color: #6592cf;
    height: 100px;
    width: 20px;
    border-radius: 0 0 10px 10px;
  }

  .caps-div {
    width: 140px;
    height: 20px;
    position: absolute;
    top: -10px;
    display: flex;
    justify-content: space-between;
  }
  .caps {
    background-color: #060f55;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    top: -10px;
    display: flex;
  }
</style>
```
