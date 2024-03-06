# [79. Tambourine](https://cssbattle.dev/play/79)

![](https://cssbattle.dev/targets/79.png)

```HTML
<div class="ring"><div class="handle"></div></div>
<div class="dot"></div>
<div class="delete-handle">
<style>
  body {
    background: #6592CF;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .ring {
    background: none;
    border: 10px solid #243D83;
    height: 150px;
    width: 150px;
    border-radius: 50%;
    position: absolute;
    top: 75px;
    overflow: hidden; 
  }
  .handle {
    background: #6592CF;
    border: 10px solid #243D83;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    bottom: -85px;
    left: 15px;
  }
  .delete-handle {
	background: #6592CF;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    top: 210px;
  }
  .dot, ::before, ::after {
    height: 50px;
    width: 50px;
    border-radius: 50%;
    background: radial-gradient(#243D83 0 5px,
    #6592CF 5px 15px,
    #243D83 15px 100%);
    position: absolute;
    top: 55px;
  }
  
  .dot::before {
    content: "";
    transform: translate(-70px, -15px);
    -webkit-box-reflect: below 20px
  }
  .dot::after {
    content: "";
    transform: translate(70px, -15px);
    -webkit-box-reflect: below 20px
  }
</style>

```
