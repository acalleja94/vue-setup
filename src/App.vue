<template>
  <div>
    Vue 3!
  </div>

  <aboutMe />
</template>

<script>
import aboutMe from "./components/about.vue";

export default {
  name: 'App',
  components: {
        aboutMe
    }
}
</script>

<style>

</style>