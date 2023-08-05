<script setup lang="ts"></script>

<template>
  <h1 class="bouncing-text">
    <span id="bounce-1">D</span>
    <span id="bounce-2">e </span>
    <span>&nbsp;</span>
    <span id="bounce-3">b</span>
    <span id="bounce-4">e</span>
    <span id="bounce-5">s</span>
    <span id="bounce-6">t</span>
    <span id="bounce-7">e </span>
    <span>&nbsp; </span>
    <span id="bounce-8">ø</span>
    <span id="bounce-9">y</span>
    <span id="bounce-10">e</span>
    <span id="bounce-11">b</span>
    <span id="bounce-12">l</span>
    <span id="bounce-13">i</span>
    <span id="bounce-14">k</span>
    <span id="bounce-15">k</span>
    <span id="bounce-16">e</span>
    <span id="bounce-17">n</span>
    <span id="bounce-18">e</span>
    <span>&nbsp;</span>
    <span id="bounce-19">i</span>
    <span>&nbsp;</span>
    <span id="bounce-20">s</span>
    <span id="bounce-21">t</span>
    <span id="bounce-22">u</span>
    <span id="bounce-23">d</span>
    <span id="bounce-24">i</span>
    <span id="bounce-25">e</span>
    <span id="bounce-26">t</span>
    <span id="bounce-27">i</span>
    <span id="bounce-28">d</span>
    <span id="bounce-29">e</span>
    <span id="bounce-30">n</span>
  </h1>
</template>

<style scoped>
.bouncing-text {
  position: relative;
  display: flex;
}
h1 {
  text-shadow: 0 1px 0 #dedc42, 0 2px 0 #dad842, 0 0 5px rgba(0, 0, 0, 1),
    0 1px 3px rgba(0, 0, 0, 0.3), 0 3px 5px rgba(0, 0, 0, 2),
    0 5px 10px rgba(0, 0, 0, 2.5), 0 10px 10px rgba(0, 0, 0, 2),
    0 20px 20px rgba(0, 0, 0, 1.5);
}
@keyframes bounce {
  0%,
  25% {
    transform: scale(1, 1) translateY(0);
  }
  2.5% {
    transform: scale(1.1, 0.9) translateY(0);
  }
  7.5% {
    transform: scale(0.9, 1.1) translateY(-55px);
  }
  12.5% {
    transform: scale(1.05, 0.95) translateY(0);
  }
  14.5% {
    transform: scale(1, 1) translateY(-7px);
  }
  16.25% {
    transform: scale(1, 1) translateY(0);
  }
  100% {
    transform: scale(1, 1) translateY(0);
  }
}

#bounce-1 {
  animation: bounce 8s ease infinite;
}
#bounce-2 {
  animation: bounce 8s ease infinite 0.1s;
}
#bounce-3 {
  animation: bounce 8s ease infinite 0.2s;
}
#bounce-4 {
  animation: bounce 8s ease infinite 0.3s;
}
#bounce-5 {
  animation: bounce 8s ease infinite 0.4s;
}
#bounce-6 {
  animation: bounce 8s ease infinite 0.5s;
}
#bounce-7 {
  animation: bounce 8s ease infinite 0.6s;
}
#bounce-8 {
  animation: bounce 8s ease infinite 0.7s;
}
#bounce-9 {
  animation: bounce 8s ease infinite 0.8s;
}
#bounce-10 {
  animation: bounce 8s ease infinite 0.9s;
}
#bounce-11 {
  animation: bounce 8s ease infinite 1s;
}
#bounce-12 {
  animation: bounce 8s ease infinite 1.1s;
}
#bounce-13 {
  animation: bounce 8s ease infinite 1.2s;
}
#bounce-14 {
  animation: bounce 8s ease infinite 1.3s;
}
#bounce-15 {
  animation: bounce 8s ease infinite 1.4s;
}
#bounce-16 {
  animation: bounce 8s ease infinite 1.5s;
}
#bounce-17 {
  animation: bounce 8s ease infinite 1.6s;
}
#bounce-18 {
  animation: bounce 8s ease infinite 1.7s;
}
#bounce-19 {
  animation: bounce 8s ease infinite 1.8s;
}
#bounce-20 {
  animation: bounce 8s ease infinite 1.9s;
}
#bounce-21 {
  animation: bounce 8s ease infinite 2s;
}
#bounce-22 {
  animation: bounce 8s ease infinite 2.1s;
}
#bounce-23 {
  animation: bounce 8s ease infinite 2.2s;
}
#bounce-24 {
  animation: bounce 8s ease infinite 2.3s;
}
#bounce-25 {
  animation: bounce 8s ease infinite 2.4s;
}
#bounce-26 {
  animation: bounce 8s ease infinite 2.5s;
}
#bounce-27 {
  animation: bounce 8s ease infinite 2.6s;
}
#bounce-28 {
  animation: bounce 8s ease infinite 2.7s;
}
#bounce-29 {
  animation: bounce 8s ease infinite 2.8s;
}
#bounce-30 {
  animation: bounce 8s ease infinite 2.9s;
}
</style>
