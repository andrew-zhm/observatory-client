<template>
  <div class="row pb-12">
    <ExploreChild/>
    <ExploreChild/>
    <ExploreChild/>
  </div>
</template>

<script>
  import ExploreChild from './exploreChild.vue'

  export default {
    name: 'main_developers',
    components: {
      ExploreChild
    }
  }
</script>
