<template>
  <div class="">
    <div class="md-caption">
      {{ label }}
    </div>
    <div class="md-title padding-xs-top ">
      {{ caption }}
    </div>
  </div>
</template>

<script>
export default {
  props: {
    label: null,
    caption: null
  },
  data () {
    return {}
  }
}
</script>

<style>
</style>
