# [89. Summit](https://cssbattle.dev/play/89)

![](https://cssbattle.dev/targets/89.png)

```HTML
<div class="pyramid"></div>
<div class="sun">
  <div class="pyramid-in"></div>
</div>


<style>
  body {
    background-color: #191919;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .sun {
    background-color: #F9E492;
    height: 200px;
    width: 200px;
    border-radius: 50%;
  	overflow: hidden;
  }
  
  .pyramid {
    border-bottom: 140px solid #4F77FF;
    height: 0px;
    width: 0px;
    border-left: 140px solid transparent;
    border-right: 140px solid transparent;
    position: absolute;
    bottom: 0; 

  }
  
  .pyramid-in {
    border-bottom: 140px solid #191919;
    height: 0px;
    width: 0px;
    border-left: 140px solid transparent;
    border-right: 140px solid transparent;
    position: relative;
	left: -40px;
    top: 110px;

  }
</sytle>
```
