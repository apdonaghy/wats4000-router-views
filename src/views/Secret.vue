<template>
  <div class="component">
    <h2>{{ message }}</h2>
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: 'Vue.js features an incrementally adaptable architecture that focuses on declarative rendering and component composition. Advanced features required for complex applications such as routing, state management and build tooling are offered via officially maintained supporting libraries and packages, with Nuxt.js as one of the most popular solutions. Vue.js lets you extend HTML with HTML attributes called directives. The directives offer functionality to HTML applications, and come as either built-in or user defined directives.'
    }
  }
}
</script>

<style scoped>
  .component {
    background: #e8e8e8;
    min-height: 400px;
  }
</style>
