# [107. Sealing Wand](https://cssbattle.dev/play/107)

![](https://cssbattle.dev/targets/107.png)

```HTML
<div class="hair"></div>
<div class="eye"></div>
<div class="eyebg"></div>
<div class="beak"></div>
<div class="stem"></div>
<div class="cap"></div>

<style>
  body {
    background: #161616;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .hair {
    background: #FFFFFF;
    width: 54px;
    height: 13px;
    position: absolute;
    top: 132px;
    left: 131px;
    z-index: 2;
    border-radius: 0 0 0 50px;
    box-shadow: 14px 11px #FFFFFF, 28px 23px #FFFFFF;
  }
  .eye {
    position: absolute;
    width: 50px;
    aspect-ratio: 1;
    border-radius: 50%;
    background-image: radial-gradient(#161616, #161616 10px, #A22015 10px, #A22015 15px, #FFFFFF 15px, #FFFFFF 25px);
    z-index: 5;
  }
  .eyebg {
    height: 60px;
    aspect-ratio: 1;
    background: #A22015;
    position: absolute;
    border-radius: 50%;
  }
  .beak {
    position: absolute;
    background-color: #E96A23;
    width: 80px;
    height: 40px;
    border-radius: 0 100px 10px 0;
    translate: 41px -1px;
    z-index: -1;
  }

  .stem {
    background-color: #E96A23;
    padding: 60px 10px;
    position: absolute;
    bottom: 0;
  }

  .cap {
    background-color: #A22015;
    width: 30px;
    aspect-ratio: 1;
    border-radius: 0 0 10px 10px;
    position: absolute;
    bottom: 97px;
  }
</style>

```
