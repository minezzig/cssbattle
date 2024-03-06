# [70. Froggy](https://cssbattle.dev/play/70)

![](https://cssbattle.dev/targets/70.png)

```HTML

<div class="face"></div>
<div class="socket left-socket"></div>
<div class="socket right-socket"></div>
<div class="shadow"></div>
<div class="nose left-nose"></div>
<div class="nose right-nose"></div>
<div class="eye left-eye"></div>
<div class="eye right-eye"></div>


<style>
  body {
    background: #293462;
    margin: 0;
    border: 0;
  	display: flex;
    justify-content: center;
    align-items: center;
  }
  .face {
    background: #FE5F55;
    height: 100px;
    width: 150px;
    border-radius: 70px;
    position: absolute;
    top: 110px;
  }
  .socket {
    background: #FE5F55;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
  }
  .left-socket {
    left: 140px;
    top: 85px;   
  }
  .right-socket {
    right: 140px;
    top: 85px;   
  }
  .eye {
    background: #293462;
    border-radius: 50%;
    height: 10px;
    width: 10px;
    border: 10px solid #FFF1C1;
    position: absolute;
  }
  .left-eye {
    left: 150px;
    top: 95px;
  }
  .right-eye {
    right: 150px;
    top: 95px;
  }
  .nose {
    background: #293462;
    border-radius: 50%;
    height: 10px;
    width: 10px;
    position: absolute;
  }
  .left-nose {
    left: 185px;
    bottom: 130px;
  }
  .right-nose {
    right: 185px;
    bottom: 130px;
  }
  .shadow {
    width: 150px;
    height: 200px;
    background: transparent;
    border-radius:50px;
    border: 35px solid #A64942;
    border-top: transparent ;
    border-left: transparent ;
    border-right: transparent ;
    z-index: 5;
    position: absolute;
    bottom: 90px;
  }
    
</style>

```
