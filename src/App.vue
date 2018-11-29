<template>
  <div id="app">
    <password-validator/>
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
