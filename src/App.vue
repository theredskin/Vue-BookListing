<template>
  <div id="app">
    <img src="./assets/logo.png">
    <book-list></book-list>
  </div>
</template>

<script>
import BookList from './components/BookList';
import BookList from './components/BookList.vue';

export default {
  name: 'app',
  components: {
    BookList
    BookList,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
