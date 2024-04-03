# [189. Triangle Hook](https://cssbattle.dev/play/189)

![](https://cssbattle.dev/targets/189.png)

```HTML
<div class="arrow"></div>
<div class="tri">
  <div class="bar"></div>
</div>


<style>
  body {
    background-color: #D669EC;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .arrow{
    width: 110px;
    background-color: #FDFBF8;
    height: 80px;
    clip-path: polygon( 0 50%, 80px 0, 80px 15px, 50px 30px, 100% 30px, 100% 50px, 50px 50px, 80px 65px, 80px 80px, 0 50%);
  }
  .tri {
    width: 0;
    height: 0;
    border-top: 90px solid transparent;
    border-bottom: 90px solid transparent;
    border-right: 0;
    border-left: 180px solid #FDFBF8;
    position: relative;
  }

  .bar {
    height: 80px;
    width: 20px;
    background-color: #D669EC;
    position: absolute;
    right: 50px;
    bottom: -40px;
  }
</style>


```
