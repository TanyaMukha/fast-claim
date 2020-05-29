<template>
  <div id="doc-header">
    <p>
      {{ manager.post }} {{ enterpriseName }}<hr>
      {{ manager.name }}<hr>
      {{ employee.post }}<hr>
      {{ employee.department }}<hr>
      {{ employee.name }}<hr>
    </p>
  </div>
</template>

<script>
export default {
  name: 'doc-header',
  data () {
    return {
      enterpriseName: "ООО Рога и копыта",
      manager: {
        name: "Иванову И.И.",
        post: "Генеральному директору"
      }
      employee: {
        name: "Петрова П.П.",
        post: "инженера 1 кат.",
        department: "отдела АБВГД"
      }
    }
  }
}
</script>
