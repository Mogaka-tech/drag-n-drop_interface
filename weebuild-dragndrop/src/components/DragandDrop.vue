<template>
  <div class="drag-n-drop-wrapper">
    <div class="dd-sidebar"><h1>Drag</h1></div>
    <div class="dd-content"><h1>Drop</h1></div>
  </div>
</template>

<script>
export default {
  name: "DragDrop",
};
</script>

<style scoped>
.drag-n-drop-wrapper {
  display: grid;
  grid-template-columns: 300px 1fr;
  grid-template-rows: repeat(3, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  grid-column-gap: 10px;
  grid-row-gap: 6px;
}

.dd-sidebar {
  border: 1px solid black;
  grid-row-start: 1;
  grid-row-end: 3;
  height: 90vh;
}
.dd-content {
  border: 1px solid black;
  height: 90vh;
}
</style>
