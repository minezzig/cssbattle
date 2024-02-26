# [33. Birdie](https://cssbattle.dev/play/33)

![](https://cssbattle.dev/targets/33.png)

```HTML
<div></div>
<p>
<style>
  body {
    background: #1A4341;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    display: grid;
  }
  div {
    margin: auto;
    border-radius: 50%;
    width: 150px;
    aspect-ratio: 1;
    background-image: conic-gradient(#998235, #998235 45deg,
         #F3AC3C 45deg, #F3AC3C 135deg,
         #1A4341 135deg, #1A4341 225deg,
         #998235 225deg);
    border: 25px solid #1A4341;
    border-right: 25px solid #F3AC3C;
    rotate: -45deg;
    position: relative;
  }
  p {
    background: #0B2429;
    height: 30px;
    aspect-ratio: 1;
    position: absolute;
    border-radius: 50%;
    margin: 0;
    left: 155px;
    top: 105px
  }
</style>

```
