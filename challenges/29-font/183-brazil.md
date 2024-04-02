# [183. Brazil](https://cssbattle.dev/play/183)

![](https://cssbattle.dev/targets/183.png)

```HTML
<div class="diamond">
  <div class="globe">
    <div class="line"></div>
  </div>
</div>
<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: #009B3A;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .diamond {
    background: #FEDF00;
    width: 300px;
    height: 200px;
    clip-path: polygon(50% 0, 100% 50%, 50% 100%, 0 50%);
    position: relative;
  }

  .globe {
    background-color: #002776;
    height: 120px;
    width: 120px;
    border-radius: 50%;
    top: 50%;
    left: 50%;
    translate: -50% -50%;
    position: relative;
   overflow: hidden;
  }

  .line {
    border: 10px solid white;
    border-radius: 50%;
    height: 200px;
    width: 200px;
    position: absolute;
    right: -20px;
    top: 30px
  }
</style>

```
