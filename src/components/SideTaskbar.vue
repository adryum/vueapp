<script setup>

</script>

<template>
<div class="wrapper">
  <div class="hotbar">

  </div>
  <div class="taskbar">

  </div>
</div>
</template>

<style scoped>
.hotbar {
  flex: 0.5;
  border-radius: 10px 10px 0 0;
  background: #979797;
}
.taskbar {
  flex: 10;
  border-radius: 0 0 10px 10px;
  background: #ffffd6;

}

.wrapper{
  position: relative;
  display: flex;
  flex-direction: column;
  height: calc(100% - 20px);
  width: calc(20vw - 20px);
  margin: 10px;

  padding: 2px;
  box-sizing: border-box;
  border-radius: 12px;

  z-index: 0;
  background: #7a7a7a;
}

</style>
