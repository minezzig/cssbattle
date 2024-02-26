# [39. Sunset](https://cssbattle.dev/play/39)

![](https://cssbattle.dev/targets/39.png)

```HTML
<div class="green-circle"></div>
<div class="container">
	<div class="yellow-circle"></div>
</div>
<div class="line1"></div>
<div class="line2"></div>
<div class="line3"></div>
<div class="line4"></div>

<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .green-circle {
    background: #998235;
    height: 200px;
    width: 200px;
    border-radius: 50%;
  }

  .container {
    height: 100px;
    width: 250px;
    position: absolute;
    overflow: hidden;
  }

  .yellow-circle {
    background: #F3AC3C;
    height: 250px;
    width: 250px;
    border-radius: 50%;
    position: absolute;
    top: -75px;
  }

   .line1 {
    background: #1A4341;
    height: 20px;
    width: 300px;
    position: absolute;
	top: 80px;
  }

  .line2 {
    background: #1A4341;
    height: 20px;
    width: 300px;
    position: absolute;
	top: 120px;
  }

  .line3 {
    background: #1A4341;
    height: 20px;
    width: 300px;
    position: absolute;
	top: 160px;
  }

  .line4 {
    background: #1A4341;
    height: 20px;
    width: 300px;
    position: absolute;
	top: 200px;
</style>

```
