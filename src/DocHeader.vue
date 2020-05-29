<template>
  <div id="doc-header">
    <p>
      {{ manager.post }} {{ enterpriseName }}<br>
      {{ manager.name }}<br>
      {{ employee.post }}<br>
      {{ employee.department }}<br>
      {{ employee.name }}<br>
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
      },
      employee: {
        name: "Петрова П.П.",
        post: "инженера 1 кат.",
        department: "отдела АБВГД"
      }
    }
  }
}
</script>
