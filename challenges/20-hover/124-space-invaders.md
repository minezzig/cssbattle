# [124. Space Invaders](https://cssbattle.dev/play/124)

![](https://cssbattle.dev/targets/124.png)

```HTML
<div class="bullet"></div>
<div class="purpleTop"></div>
<div class="purpleFeet"></div>
<div class="yellowTop"></div>
<div class="yellowFeet"></div>

<style>
  body {
    background: #071945;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .purpleTop {
    height: 10px;
    width: 50px;
    background: #B069F7;
    position: absolute;
    top: 40px ;
    left: 40px;
    box-shadow: 90px 0 #B069F7, 180px 0 #B069F7, 270px 0 #B069F7
  }
  .purpleFeet {
    height: 10px;
    width: 10px;
    background: #B069F7;
    position: absolute;
    top: 50px;
    left: 30px;
    box-shadow: 60px 0 #B069F7,
                90px 0 #B069F7,
                150px 0 #B069F7,
                180px 0 #B069F7,
                240px 0 #B069F7,
                270px 0 #B069F7,
                330px 0 #B069F7
  }
  .yellowFeet {
    height: 10px;
    width: 10px;
    background: #F8DA37;
    position: absolute;
    top: 100px;
    left: 30px;
    box-shadow: 60px 0 #F8DA37,
            
                180px 0 #F8DA37,
                240px 0 #F8DA37,
                270px 0 #F8DA37,
                330px 0 #F8DA37
  }
    .yellowTop {
    height: 10px;
    width: 50px;
    background: #F8DA37;
    position: absolute;
    top: 90px ;
    left: 40px;
    box-shadow: 180px 0 #F8DA37, 270px 0 #F8DA37
  }
  .bullet {
    width: 10px;
    height: 10px;
    background: #2CE1EA;
    position: absolute;
    top: 210px;
    box-shadow: 0 30px #2CE1EA, 0 60px #2CE1EA,0 65px #2CE1EA;
  }
  .bullet::after {
    content: "";
    height: 30px;
    width: 30px;
    position: absolute;
    top: -10;
    translate: -10px 85px;
    background: #2CE1EA;
    
    rotate: 45deg;
  }
</style>
```
