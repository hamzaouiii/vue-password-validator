<template>
  <div id="app">
    <div class="container">
      <password-validator/>
    </div>
  </div>
</template>

<script>
import PasswordValidator from './components/PasswordValidator.vue';
export default {
  name: 'app',
  components: {
    PasswordValidator,
  }
}
</script>

<style src="./scss/style.scss" lang="scss">
</style>
