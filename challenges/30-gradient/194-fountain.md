# [194. Fountain](https://cssbattle.dev/play/1894)

![](https://cssbattle.dev/targets/194.png)

```HTML
<div class="arch single"></div>
<div class="arch double"></div>
<style>
  body {
    background: #4FA07B;
    margin: 0;
    display: grid;
    place-content: center;
  }
  .arch {
    position: absolute;
    width: 140px;
    height: 70px;
    background:radial-gradient(circle at 50% 100%,
      #4FA07B, #4FA07B 10px,
      #0D1335 10px, #0D1335 30px,
      #4FA07B 30px, #4FA07B 50px,
      #0D1335 50px, #0D1335 70px,
      transparent 70px, transparent                       
    );
  }
  .single {
    top: 20px;
    left: 130px;
  }
  .single::before {
    content: "";
    position: absolute;
    left: 0;
    top: 70px;
    width: 20px;
    height: 50px;
    background: #0D1335;
    box-shadow: 40px 0 #0D1335,
                80px 0 #0D1335,
                120px 0 #0D1335;
  }
  .double {
    bottom: 110px;
    left: 70px;
    -webkit-box-reflect: right -20px;
  }
  
  .double::after {
    content: "";
    position: absolute;
    left: 0;
    top: 70;
    height: 47px;
    width: 20px;
    background: #0D1335;
    box-shadow: 40px 0 #0D1335,
                40px 23px #0D1335,
                80px 0 #0D1335,
                80px 23px #0D1335,
                80px 43px #0D1335,
                120px 0 #0D1335,
                120px 23px #0D1335,
                120px 63px #0D1335;
  }

  
</style>

```
