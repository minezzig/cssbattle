# [136. Alien Eye](https://cssbattle.dev/play/136)

![](https://cssbattle.dev/targets/136.png)

```HTML
<div class="big">
  <div class="medium">
    <div class="small">
      <div class="inside"></div>
    </div>
  </div>
</div>
<style>
  body {
    background: #998235;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .big {
    background-color: #FCBE5C;
    height: 180px;
    width: 180px;
    border-radius: 50%;
    position: relative;
  }
  .medium {
    background-color: #0B2429;
    height: 140px;
    width: 140px;
    border-radius: 50%;
    position: absolute;
    top: 20px;
    right: 10px;
  }
  .small {
    background-color: #FCBE5C;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    top: 20px;
    left: 10px;
  }
  .inside {
    background-color: #998235;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: absolute;
    right: 10px;
    top: 20px;
  }
</style>

```
