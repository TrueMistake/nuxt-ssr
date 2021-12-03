<template>
  <div>
    <section class="hero is-medium is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <div class="hero-content">
            <h1 class="title">
              Welcome to the JavaScript SSR Blog.
            </h1>
            <h2 class="subtitle">
              Hope you find something you like.
            </h2>
          </div>
        </div>
      </div>
    </section>
    <posts />
  </div>
</template>

<script>
import Posts from '~/components/Posts'
export default {
  head: {
    title: 'Home'
  },
  components:{
    Posts
  }
}
</script>

<style>
.hero-body{
  padding: 0;
}
.hero > .container {
  min-height: 100vh;
  display: flex;
  align-items: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 50px;
  line-height: 58px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 32px;
  line-height: 38px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.main-content{
  padding: 2rem;
}
</style>

