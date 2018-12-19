<template>
  <div id="app">
    <header>
      <h3>Subreddits</h3>
    </header>
    <Subreddits category="food"> </Subreddits>
    <Subreddits category="sports"> </Subreddits>
    <Subreddits category="funny"> </Subreddits>
    <Subreddits category="pets"> </Subreddits>
    <Subreddits category="art"> </Subreddits>
    <Subreddits category="internet"> </Subreddits>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import Subreddits from './components/Subreddits'
export default {
  name: 'App',
  components: {
    Subreddits
  }
}
</script>

<style>
  body {
    font-family: arial;
    color: #666666;
    background: #f4f4f4;
    margin: 0;
    padding: 0;
  }

  a {
    text-decoration: none;
  }

  header {
    background: coral;
    color: #ffffff;
    padding: 10px;
    text-align: center;
  }
</style>
