# [187. Striped Triangle](https://cssbattle.dev/play/187)

![](https://cssbattle.dev/targets/187.png)

```HTML
<div></div>
<style>
  body {
    background-color: #40234B;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    width: 230px;
    height: 200px;
    /* clip-path: polygon(0% 0, 100% 0%, 50% 100%); */
    clip-path: polygon(50% 0, 100% 100%, 0 100%);
background-image: repeating-linear-gradient(to top, #A94EA4, 
          #A94EA4 17px, 
          #40234B 17px, 
          #40234B 27px);
   transform: rotate(-60deg) translate(30px, -50px);
  }
 
</style>
```
