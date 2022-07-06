<template>
  <div class="full-section" ref="full-section">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'FullPage',
    props: {
      backgroundImage: String,
      backgroundColor: String,
    },
    mounted() {
      if (this.backgroundImage) {
        this.$refs['full-section'].style.backgroundImage = `url(${this.backgroundImage})`
      }
      if (this.backgroundColor) {
        this.$refs['full-section'].style.backgroundColor = this.backgroundColor
      }
    },
    methods: {
      
    },
  }
</script>

<style scoped>
.full-section {
  width: 100%;
  height: 100vh;
}
</style>