<template functional>
  <div class="md-container">
    <div class="dynamic-content" v-html="props.md"></div>
  </div>
</template>

<script>
export default {
  name: 'MdContainer',
  props: {
    md: {
      type: String,
      default: ''
    }
  }
};
</script>

<style lang="scss" scoped>
.md-container {
  padding: 20px;
}
</style>

<style lang="scss">
@import 'MdContainer.scss';
</style>
