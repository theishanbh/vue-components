<template>
  <div>Hello {{name}}. your hero is {{heroName}} </div>
</template>

<script>
export default {
  name: 'Greet',
  // props: ['name','heroName']
  props: {
    name : String,
    heroName : String
  }
}
</script>

