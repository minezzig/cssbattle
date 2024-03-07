# [84. Junction](https://cssbattle.dev/play/84)

![](https://cssbattle.dev/targets/84.png)

```HTML
<div class="line1"></div>
<div class="line2"></div>
<div class="line3"></div>
<div class="line4"></div>
0
<style>
body {
  margin: 0;
  padding: 0;
  background-color: #191919;
  display: flex;
  align-items: center;
  
}

  .line1 {
    background-color: #A64942;
    width: 180px;
    height: 40px;
    border-radius: 0 20px 20px 0;
    position: absolute;
  }
  .line2 {
    background-color: #A64942;
    width: 180px;
    height: 40px;
    border-radius: 20px 0 0 20px ;
    position: absolute;
    right: 0;
  }

  .line3 {
    background-color: #FE5F55;
    height: 180px;
    width: 40px;
    border-radius: 0 0 20px 20px;
    position: absolute;
    top: -50;
    left: 180px;
  }
  .line4 {
    background-color: #FE5F55;
    height: 180px;
    width: 40px;
    border-radius: 20px 20px 0 0;
    position: absolute;
    bottom: -50;
    left: 180px;
    right: 0;
  }
</style>
```
