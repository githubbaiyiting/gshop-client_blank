<template>

  <header class="header">
    <slot name="header_left"></slot>
    <span class="header_title">
      <span class="header_title_text ellipsis">{{title}}</span>
    </span>
    <slot name="header_right"></slot>
  </header>
</template>

<script>
export default {
  props: {
    title: String
  }
}
</script>

<style scoped>

</style>
<style lang="stylus" rel="stylesheet/stylus">
</style>
