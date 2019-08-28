<template>
  <div class="container">
    {{ testProps }}, this is custom comp
  </div>
</template>

<script>
export default {
  name: 'Custom',
  props: {
    testProps: {
      type: String,
      default: 'hello'
    }
  },
  data() {
    return {

    }
  },
  mounted() {

  },

  methods: {

  }
}
</script>

<style scoped lang='scss'>
  @import "~@/styles/variables.scss";

  .container{
    color: $yellow;
  }
</style>
