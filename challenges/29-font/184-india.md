# [184. India](https://cssbattle.dev/play/184)

![](https://cssbattle.dev/targets/184.png)

```HTML
<div class="wheel">
  <div class="stick"></div>
</div>
<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: linear-gradient(to bottom,
      #F19E4B 33.3%, #FFFFFF 33.3% 66.6%, #3F8627 66.6%);
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .wheel {
    background-color: #00007B;
    height: 20px;
    width: 20px;
    border-radius: 50%;
    border: solid 20px #fff;
    box-shadow: 0 0 0 10px #00007B; 
    position: relative;
  }

  .stick, .stick::before, .stick::after {
    background-color: #00007B;
    width: 4px;
    height: 60px;
    position: absolute;
  }

  .stick {
    top: -20px;
    left: 8px;
  }

  .stick::before {
    content: "";
    rotate: 60deg;
  }

    .stick::after {
    content: "";
    rotate: -60deg;
  }
</style>

```
