<template>
  <div class="home">
    <img src="@/assets/vue-logo.png" alt="vue logo.">
    <h1>Welcome to the VueJS Shanghai Meetup!
    </h1>
    <h2>Vue is coming...</h2>
    <a href="https://vuejs.org/v2/guide/">Get Started with Vue</a>
  </div>
</template>

<script>
  // @ is an alias to /src

  export default {
    name: 'home',
    components: {
    }
  }
</script>

<style lang="less">
  .home {
    text-align: center;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  h1,
  h2 {
    color: white;
    margin-bottom: 60px;
  }

  h1 {
    font-weight: 700;
  }

  h2 {
    font-weight: 400;

  }

  img {
    width: 300px;
  }

  a {
    color: #fff;
    text-decoration: none;
    background: linear-gradient(-200deg, #ff2a30, #8c0a1d);
    padding: 20px;
    border-radius: 5px;
    font-weight: 700
  }
</style>