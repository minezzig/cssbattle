# [127. Letter I](https://cssbattle.dev/play/127)

![](https://cssbattle.dev/targets/127.png)

```HTML
<div class="line top"></div>
<div class="stem"></div>
<div class="line bottom"></div>

<style>
  body {
    background: #E3516E;
    margin: 0;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
  }
  .stem {
    width: 30px;
    height: 100px;
    background: #FADE8B;
    position: relative;
  }
  .line {
    width: 100px;
    height: 30px;
    background: #FADE8B;
    border-radius: 50px;
    position: relative;
  }
  .stem::before, .stem::after {
    content: "";
    height: 15px;
    aspect-ratio: 1;
    position: absolute;
    background: radial-gradient(circle at 0 100%, #E3516E, #E3516E 50%, #FADE8B 50%, #FADE8B);
    -webkit-box-reflect: right 22px;
  }
  .stem::before{
    left: -11px;
    top: -5px;
  }
  .stem::after{
    rotate: 180deg;
    right: -11px;
    bottom: -5px;
  }

  .top::after, .bottom::before {
    content: "";
    background: #FADE8B;
    border-radius: 50%;
    height: 30px;
    aspect-ratio: 1;
    position: absolute;
  }
  .top::after {
    right: -40px
  }
  .bottom::before {
    left: -40px
  }
</style>

```
