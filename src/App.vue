<template>
  <div id="app">
    <Calendar 
    render-style="background" 
    :min-date="new Date()"
    ></Calendar>
  </div>
</template>

<script>
import Calendar from 'v-year-calendar';
export default {
  name: 'App',
  components: {
    Calendar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
