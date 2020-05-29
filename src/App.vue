<template>
  <div id="app">
    <doc1>

    </doc1>
  </div>
</template>

<script>
import Doc1 from "./Doc1.vue";
export default {
  name: 'app',
  components: {
    'doc1': Doc1
  }
}
</script>

<style>
@font-face {
  font-family: "Eskal Font4You";
  src: url("~/src/assets/fonts/Eskal Font4You.ttf");
}

#app {
  font-family: "Eskal Font4You";
}
</style>
