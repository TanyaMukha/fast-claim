<template>
  <div id="document">
    <div id="doc-header">

    </div>

    <div id="claim">
      <h1>{{ title }}</h1>
      <div id="doc">

      </div>
    </div>
    <div id="doc-footer">

    </div>
  </div>
</template>

<script>
export default {
  name: 'document',
  data () {
    return {
      title: "Заявление"
    }
  }
}
</script>
