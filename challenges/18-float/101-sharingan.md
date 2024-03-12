# [101. Sharingan](https://cssbattle.dev/play/101)

![](https://cssbattle.dev/targets/101.png)

```HTML
<div class="main">
  <div class="ear"></div>
</div>
<style>
  body {
    background-color: #161616;
    display: flex;
    align-items: center;
    justify-content: center;
    box-sizing: border-box;
  }
  .main {
    width: 200px;
    height: 200px;
    background: radial-gradient(circle, 
        black 0,
        black 25px,
        #E96A23 25px,
        #E96A23 35px,
        black 35px,
        black 50px,
        #A22015 50px,
        #A22015 95px,
        black 95px,
        black 100px);
    border-radius: 50%;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .ear, .ear:before, .ear:after {
    height: 72px;
    width: 72px;
    border-radius: 50%;
    border: 15px solid #000000;
  }
  .ear {
    transform: translate(-75px, -43px);
  }
  .ear:before {
    content: "";
    display: inline-block;
    position: absolute;
     transform: translate(135px, -15px);
  }
  .ear:after {
    content: "";
    display: inline-block;
    position: absolute;
    transform: translate(60px, 115px);
  }

</style>



```
