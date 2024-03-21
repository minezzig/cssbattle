# [153. Checkers](https://cssbattle.dev/play/153)

![](https://cssbattle.dev/targets/153.png)

```HTML
<div class="container">
<p><p><p><p><p>
<p><p><p><p><p>
<p><p class="blank">
<p><p class="blank"><p>
<p><p><p><p><p>
<p><p><p><p><p>
</div>
  <style>
  body {
    background: #E3516E;
    margin: 0;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .container {
    width: 200px;
    aspect-ratio: 1;
    background: #FADE8B;
    display: grid;
    grid-template: repeat(5, 1fr) / repeat(5, 1fr)
  }
  p:nth-child(even){
    background: radial-gradient(#FADE8B, #FADE8B 35%, #E3516E 35%, #E3516E);
    margin: 0;
  }

  .blank {
    background: #E3516E !important;
  }
  
</style>

<div class=""></div>
<div class="circle"></div>
<div class=""></div>
<div class="circle"></div>
<div class=""></div>

<div class="circle"></div>
<div class=""></div>
<div class="circle"></div>
<div class=""></div>
<div class="circle"></div>

<div class=""></div>
<div class="pink"></div>
<div class=""></div>
<div class="pink"></div>
<div class=""></div>

<div class="circle"></div>
<div class=""></div>
<div class="circle"></div>
<div class=""></div>
<div class="circle"></div>

<div class=""></div>
<div class="circle"></div>
<div class=""></div>
<div class="circle"></div>
<div class=""></div>
```
