# [76. Beeee](https://cssbattle.dev/play/76)

![](https://cssbattle.dev/targets/76.png)

```HTML
<div class="body"></div>
<div class="eye"></div>
<div class="wing"></div>


<style>
  body {
    background:#998235;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .body {
    background: linear-gradient(to right, 
      							#191919 25px, 
      							#EFF33C 25px 35px, 
      							#191919 35px 60px, 
      							#EFF33C 60px 70px, 
      							#191919 70px 95px, 
      							#EFF33C 95px 100%);
    width: 150px;
    height: 75px;
    border-radius: 50px 50px;
    position: absolute;
    bottom: 75px;
  }
  
  .eye {
    background: #191919;
    height: 15px;
    width: 15px;
    border-radius: 50%;
    position: absolute;
    right: 145px;
    bottom: 115px;
  }
  
  .wing {
    background: #FFFFFF;
    border-radius: 50% 50% 0 50%;
    height: 75px;
    width: 75px;
    position: absolute;
    bottom: 150px;
    left: 125;
    -webkit-box-reflect: right;
  }

</style>
```
