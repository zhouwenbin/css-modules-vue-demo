<template>
  <div id="app">
    <h1 class="{{styles.red}}">{{ msg }}</h1>
  </div>
</template>

<script>
import styles from '!style!css?module!./App.css';
export default {
  data () {
    return {
      styles:styles,
      msg: 'Hello Vue!'
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
