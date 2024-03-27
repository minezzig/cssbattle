# [169. Abstract Plate](https://cssbattle.dev/play/169)

![](https://cssbattle.dev/targets/169.png)

```HTML
<div class="out"></div>
<div class="in"></div>
<div class="in right"></div>

<style>
  * {
    background: radial-gradient(circle,
      #4FA07B 55px, 0,
      #0D1335 65px, 0,
      #4FA07B 85px, 0,
      #0D1335 95px, 0,
      #4FA07B 115px, 0,
      #0D1335 125px, 0,
      #4FA07B 135px
    )
  }
  .out {
    position: absolute;
    left: 45px;
    top: 32px;
    width: 310px;
    height: 236px;
    background: #FBFAE2;
    clip-path: polygon(0 0, 0 100%, 50% 59%, 100% 100%, 100% 0, 50% 41%);
  }
  .in {
    position: fixed;

    inset: 0;
    clip-path: polygon(55px 49px, 55px 249px, 190px 165px, 166px 149px, 190px 133px);
  }
  .right{
    scale: -1;

  }
</style>

```
