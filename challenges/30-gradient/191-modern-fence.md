# [191. Modern Fence](https://cssbattle.dev/play/191)

![](https://cssbattle.dev/targets/191.png)

```HTML
<div class="diagonal"></div>
<div class="line"></div>
<div class="cover"></div>

<style>
  body {
    background-color: #2F2E59;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .cover, .cover::after {
    background-color: #2F2E59;
    height: 50px;
    width: 30px;
    position: absolute;
    left: 47px;
  }
  .cover::after {
    content: "";
    left: 276px;
  }

  .diagonal {

    width: 20px;
    height: 278px;
    background: #EEECF6;
    rotate: -60deg;
    border-radius: 15px;
    box-shadow: -57px 0  #EEECF6,
                 57px 0  #EEECF6;
  }
  .line {
    width: 20px;
    height: 150px;
    background: #EEECF6;
    border-radius: 15px;
    position: absolute;
    left: 77px;
    box-shadow: 226px 0 #EEECF6;
  }

</style>


```
