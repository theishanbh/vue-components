<template>
  <div>Hello {{name}}. your hero is {{heroName}} </div>
</template>

<script>
export default {
  name: 'Greet',
  props: ['name','heroName']
}
</script>

