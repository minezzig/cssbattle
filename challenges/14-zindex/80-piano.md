# [80. Piano](https://cssbattle.dev/play/80)

![](https://cssbattle.dev/targets/80.png)

```HTML
<div class="piano">
  <p><p><p><p><p><p><p>
  <div class="black a"></div>
  <div class="black b"></div>
  <div class="black c"></div>
</div>

<style>
  body {
    background: #998235;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .piano {
    background: #191919;
    height: 100px;
    width: 180px;
    display: flex;
    justify-content: space-evenly;
    align-items: flex-end;
    border-radius: 10px;
  }
  p {
    height:70px;
    width: 20px;
    background: #FFFFFF;
    border-radius: 5px;
    margin: 0 0 5px 0;
    padding: 0px;
  }
  .black {
    background: black;
    height: 35px;
    width: 15px;
    position: absolute;
    bottom: 140px;
  }
  .a {
    left: 130px; 
    -webkit-box-reflect: right 10px;
  }
  .b {
    left: 230px;
    -webkit-box-reflect: left 10px;
  }
  .c {
    left: 255px;
  }

</style>
```
