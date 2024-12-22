<script setup>
defineProps({
  TextThin: String,
  TextBold: String,
})
</script>
<template>
  <h1>
    <p class="title_gray uppercase">{{ TextThin }}</p>
    <p class="title_black uppercase">{{ TextBold }}</p>
  </h1>
</template>

<style scoped>
.title_gray,
.title_black {
  font-size: 64px;
  line-height: 64px;
}

.title_gray {
  margin-top: 336px;
  font-family: 'TTHoves-300';
  color: #bdbdbd;
}

.title_black {
  font-family: 'TTHoves-700';
  color: #333333;
  margin-bottom: 90px;
}
</style>
