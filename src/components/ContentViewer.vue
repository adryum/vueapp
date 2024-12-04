<script setup>
import '../assets/main.css';
</script>

<template>
<div class="wrapper">

</div>
</template>

<style scoped>
.wrapper{
  display: flex;
  flex-direction: column;

  border-radius: var(--border-radius-small);;
  height: calc(100% - 20px);
  width: calc(80vw - 10px);
  margin: 10px 10px 10px 0;

  overflow: hidden;
  z-index: 1;
  background: var(--very-dark);
}
.wrapper::before{
  content: '';

  border-radius: calc(var(--border-radius-small) - 2px);
  height: calc(100% - var(--border-width-small) * 2);
  width: calc(100% - var(--border-width-small) * 2);
  transform: translateX(var(--border-width-small)) translateY(var(--border-width-small));


  filter: brightness(var(--hundred-seventy-five-percent));
  background: var(--very-dark);
}
</style>