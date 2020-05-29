<template>
  <div id="document">
    <doc-header>

    </doc-header>

    <div id="claim">
      <h1>{{ title }}</h1>
      <div id="doc">
          <p>Прошу дать мне отпуск с 01.04.2020 на 24 дня согласно графику отпусков.</p>
      </div>
    </div>
    <doc-footer>

    </doc-footer>
  </div>
</template>

<script>
import DocHeader from "./DocHeader.vue";
import DocFooter from "./DocFooter.vue";
export default {
  name: 'document',
  title: "Заявление",
  components: {
      'doc-header': DocHeader,
      'doc-footer': DocFooter
  }
}
</script>
