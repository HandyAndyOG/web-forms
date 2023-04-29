<template> 
  <SignupForm />
</template>

<script>
import SignupForm from './components/SignupForm.vue';
export default {
  name: 'App',
  components: {
    SignupForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
body {
  background: #2c3e50;
  margin: 0;
}
</style>
