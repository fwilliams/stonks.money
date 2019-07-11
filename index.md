---
layout: default
---

<div class="container">
  <div class="sliding-background"></div>
</div>


<style>
html, body {margin: 0; height: 100%; overflow: hidden}

.container {
  overflow: hidden;
  height:100%
}

.sliding-background {
  background: url("assets/img/stonks.jpg") repeat;
  height: 11880px;
  width: 8920px;
  animation: slide 40s linear infinite;
}

@keyframes slide{
  0%{
    transform: translate3d(-4460px, 0, 0);
  }
  100%{
    transform: translate3d(0px, -2376px, 0);
  }
}
</style>
