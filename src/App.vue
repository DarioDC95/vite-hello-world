<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="title">
    <AppTitle />
  </div>
  <AppHero />
</template>

<style>
  .title {
    margin-bottom: 30px;
  }
</style>
