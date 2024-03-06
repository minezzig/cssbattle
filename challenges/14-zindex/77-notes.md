# [77. Notes](https://cssbattle.dev/play/77)

![](https://cssbattle.dev/targets/77.png)

```HTML
<div class="eighth-note"></div>
<div class="eighth-note-stem"></div>
<div class="quarter-note"></div>
<div class="quarter-note-stem"></div>
<div class="sixteenth-note"></div>
<div class="sixteenth-note-stem"></div>

<style>
  body {
    background: #191919;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .eighth-note {
    background: #FE5F55;
    height: 40px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
    bottom: 90px;
    left: 55px;
    -webkit-box-reflect: right 20px;
  }

  .eighth-note-stem {
    background: none;
    height: 90px;
    width: 60px;
    border: 10px solid #FE5F55;
    border-bottom: none;
    position: absolute;
    left: 95px;
    top: 90px;
  }
  .quarter-note {
    background: #A64942;
    height: 40px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
    bottom: 90px;
    left: 195px;
  }
  .quarter-note-stem {
    background: none;
    height: 90px;
    width: 30px;
    border: 10px solid #A64942;
    border-bottom: none;
    border-right: none;
    position: absolute;
    left: 235px;
    top: 90px;
  }
  
  .sixteenth-note {
    background: #FE5F55;
    height: 40px;
    width: 50px;
    border-radius: 50%;
    position: absolute;
    bottom: 90px;
    right: 85px;
  }
  .sixteenth-note-stem {
    background: linear-gradient(#191919 0px 10px, 
      							#FE5F55 10px 20px, 
      							#191919 20px 100%);
    height: 90px;
    width: 30px;
    border: 10px solid #FE5F55;
    border-bottom: none;
    border-right: none;
    position: absolute;
    right: 55px;
    top: 90px;
  }
</style>

```
