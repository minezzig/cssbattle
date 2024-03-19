# [133. Sprial](https://cssbattle.dev/play/133)

![](https://cssbattle.dev/targets/133.png)

```HTML
 <div class="container topCon">
   <div class="circles circle1"></div>
 </div>
<div class="container botCon">
  <div class="circles circle2"></div>
</div>
<div class="balls"></div>
<style>
  body {
    background: #F5D6B4;
    margin: 0;
  }
  .balls, ::after {
    background-color: #D86F45;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    position: absolute;
  }
  .balls {
    left: 80px;
    top: 140
  }
  .balls::after {
    content: "";
    left: 80px;
  }
  .container {
    overflow: hidden;
    height: 100px;
    position: relative;
  }
  .topCon {
    position: absolute;
    top: 50px;
    left: 100px;
  }
  .botCon {
    position: absolute;
    left: 80px;
    bottom: 50px;
  }
  .circles{
    width: 200px;
    height: 200px;
    border-radius: 50%;
    position: relative;
  }
  .circle1 {
    background: radial-gradient(
      #F5D6B4 0 13%,
      #D86F45 13% 28%, 
      #F5D6B4 28% 42%, 
      #D86F45 42% 56%, 
      #F5D6B4 56% 100%);
  }
  .circle2 {
    bottom: 100; 
    background: radial-gradient(
      #F5D6B4 0 28%, 
      #D86F45 28% 42%, 
      #F5D6B4 42% 56%, 
      #D86F45 56% 100%);
  }

  
</style>
```
