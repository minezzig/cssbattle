# [178. Candy](https://cssbattle.dev/play/178)

![](https://cssbattle.dev/targets/178.png)

```HTML
<div class="left"></div>
<div class="rec"></div>
<div class="right"></div>
<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: #CBE8DD;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .rec {
    background: linear-gradient(110deg,
        #007192 0 60px,
        #CBE8DD 60px 70px,
        #007192 70px 79px,
        #CBE8DD 79px 89px,
        #007192 89px 98px,
        #CBE8DD 98px 108px,
        #007192 108px 117px,
        #CBE8DD 117px 127px,
        #007192 127px 136px,
        #CBE8DD 136px 146px,
        #007192 146px 200px);
    height: 100px;
    width: 180px;
    border-radius: 10px;
  }

  .left {
    height: 20px;
    width: 0;
    border-left: 30px solid #007192;
    border-right: 10px solid transparent;
    border-top: 30px solid transparent;
    border-bottom: 30px solid transparent;
  }
    .right {
    height: 20px;
    width: 0;
    border-right: 30px solid #007192;
    border-left: 10px solid transparent;
    border-top: 30px solid transparent;
    border-bottom: 30px solid transparent;
  }
</style>


```
