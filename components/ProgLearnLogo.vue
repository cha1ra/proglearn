<template>
  <img src="~/assets/img/logo.png" class="prog-learn-logo" alt="ProgLearn">
</template>

<style>
.prog-learn-logo {
  width: 180px;
  transform: rotateY(560deg);
  animation: turn 3.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>