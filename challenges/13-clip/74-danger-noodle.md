# [74. Danger Noodle](https://cssbattle.dev/play/74)

![](https://cssbattle.dev/targets/74.png)

```HTML
<div class="head"><p class="eye"></p></div>
<div class="body-top-outter"><p class="body-top-inner"></p></div>
<div class="body-bottom-outter"><p class="body-bottom-inner"></p></div>
<div class="butt"></div>
<p class="butt-inner"></p>
<div class="blackout"></div>
<div class="neck-outter"></div>
<p class="neck-inner"></p>


<style>
  body {
    background: #191919;
    border:0;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .head {
    width: 50px;
    height:30px;
    background: #E08027;
    border-radius: 18px 25px 25px 18px;
    position: absolute;
    right: 85px;
  }
  .eye {
    background: #191919;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    position: absolute;
    right: 10px;
    top: -14px;
    -webkit-box-reflect: below 6px;
  }
  .body-top-outter {
    background: #191919;
    border: 5px solid #E08027;
    height: 100px;
    width: 60px;
    border-radius: 50px 50px 0 0;
    border-bottom: none;
    position: absolute;
    top: 40px;
    left: 15px;
    -webkit-box-reflect: right 30px;

  }
  .body-top-inner {
    background: #191919;
    border: 5px solid #E08027;
    height: 70px;
    width: 30px;
    border-radius: 50px 50px 0 0;
    border-bottom: none;
    position: absolute;
    top: -6px;
    left: 10px;
  }
  
  .body-bottom-outter {
    background: #191919;
    border: 5px solid #E08027;
    height: 130px;
    width: 60px;
    border-radius: 0 0 50px 50px;
    border-top: none;
    position: absolute;
    bottom: 40px;
    left: 65px;
    -webkit-box-reflect: right 30px;

  }
  .body-bottom-inner {
    background: #191919;
    border: 5px solid #E08027;
    height: 130px;
    width: 30px;
    border-radius: 0 0 50px 50px;
    border-top: none;
    position: absolute;
    bottom: -6px;
    left: 10px;
  }
  .butt {
    background: #191919;
    border: 5px solid #E08027;
    height: 30px;
    width: 60px;
    border-radius: 0 0 50px 50px;
    border-top: none;
    position: absolute;
    left: -35px;
    top: 125px;
  }
  .butt-inner {
    background: #191919;
    border: 5px solid #E08027;
    height: 30px;
    width: 30px;
    border-radius: 0 0 50px 50px;
    border-top: none;
    position: absolute;
	left: -20px;
    top: 95px;
  }
  .blackout {
    background: #191919;
    width: 40px;
    height: 80px;
    position: absolute;
    right: 150
  }
  .neck-outter {
    background: transparent;
    border: 5px solid #E08027;
    height: 50px;
    width: 50px;
    border-radius: 35px 0 0 0;
    border-bottom: none;
    border-right: none;
    z-index: 5;
    position: absolute;
    right: 130px;
    top: 140px;
  }
  .neck-inner {
    background: transparent;
    border: 5px solid #E08027;
    height: 50px;
    width: 35px;
    border-radius: 22px 0 0 0;
    border-bottom: none;
    border-right: none;
    z-index: 6;
    position: absolute;
    right: 130px;
    top: 139px;
  }

</style>


```
