# [52. Break the Chain](https://cssbattle.dev/play/52)

![](https://cssbattle.dev/targets/52.png)

```HTML
<div class="little-flame"></div>
<div class="big-flame"></div>
<div class="pin"></div>
<div class="pin two"></div>
<div class="pin two"></div>
<div class="pin three"></div>
<div class="pin four"></div>
<div class="pin five"></div>
<div class="pin six"></div>
<div class="pin seven"></div>


<style>
  body {
    background: #6592CF;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .pin {
    background: #243D83;
    width: 10px;
    height: 50px;
    position: absolute;
    bottom: 110px;
    left: 45px;
  }
  
  .pin:after {
    content: "";
    background: #243D83;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    position: absolute;
    right: -5;
    top: -10px; 
  }

  .two {
    left: 90px
  }
  
  .three {
    left: 135px
  }
  
  .four {
    left: 210px
  }
  
  .five {
    left: 255px
  }
  
  .six {
    left: 300px
  }
  
  .seven {
    left: 345px
  }
  
  .big-flame {
    background: #EEB850;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    position: absolute;
    left: 65px;
    bottom: 140px;
  }
  
  .little-flame {
    background: #EEB850;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    position: absolute;
    left: 30px;
    bottom: 140px;
  }
  
  .little-flame:after {
    content: "";
    background: #EEB850;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    position: absolute;
    left: 90px;
  }
</style>

```
