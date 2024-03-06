# [71. Elephant](https://cssbattle.dev/play/71)

![](https://cssbattle.dev/targets/71.png)

```HTML

<div class="face"></div>
<div class="ear left-ear"></div>
<div class="ear right-ear"></div>
<div class="trunk"></div>
<div class="tusks"></div>
<div class="eye left-eye"></div>
<div class="eye right-eye"></div>
<div class="brow"></div>



<style>
  body {
    background: #998235;
    margin: 0;
    border: 0;
  	display: flex;
    justify-content: center;
    align-items: center;
  }
  .face {
    background: #1A4341;
    height: 180px;
    width: 180px;
    border-radius: 50%;
  }
  .ear {
    background: #0B2429;
    height: 180px;
    width: 80px;
    position: absolute;
    border-radius: 50%;
    z-index: -2;
  }
  .left-ear {
	left: 50px;
    box-shadow: inset 16px 0px #1A4341;
  }
   .right-ear {
	right: 50px;
    box-shadow: inset -16px 0px #1A4341;
  }
  .trunk {
    background: #0B2429;
    height: 120px;
    width: 40px;
    position: absolute;
    bottom: 0;
    border-radius: 50px 50px 0 0;
    z-index: 5;
  }
  .tusks {
    background: transparent; 
    border: 20px solid #FFFFFF;
    border-radius: 50%;
    height: 80px;
    width: 80px;
    position: absolute;
    top: 190px;
    z-index: 3;
    border-left: 20px solid transparent;
    border-bottom: 20px solid transparent;
    transform: rotate(-45deg);
  }
  .eye {
    background: #0B2429;
    height: 20px;
    width: 20px;
    position: absolute;
    border-radius: 50%;
    border: 10px solid #998235;
  }
  .left-eye {
    left: 150px;
  }  
  .right-eye {
    right: 150px;
  }
  .brow {
    background: #1A4341;
    height: 20px;
    width: 100px;
    position: absolute;
    top: 130
  }
</style>

```
