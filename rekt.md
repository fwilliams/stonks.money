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
  background: url("assets/img/stonksflipped.jpg") repeat;
  height: 11880px;
  width: 8920px;
  animation: slide 7s linear infinite;
}

@keyframes slide{
  0%{
    transform: translate3d(-792px, -446px, 0);
  }
  100%{
    transform: translate3d(0px, 0px, 0);
  }
}
</style>
