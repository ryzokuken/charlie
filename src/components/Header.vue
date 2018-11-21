<template>
  <b-jumbotron id="head">
    <template slot="header">
      Charlie
    </template>
    <template slot="lead">
      The postmodern social media platform for getting the best real news.
    </template>
    <hr class="my-4">
    <p>
      Jump in the get curated and verified articles, and sort out all the fake stuff.
    </p>
    <b-btn variant="primary" class="btn" href="#">My Feed</b-btn>
    <b-btn variant="success" class="btn" href="#">Trending</b-btn>
  </b-jumbotron>
</template>

<style scoped>
  .btn {
    margin: 5px;
  }
  
  #head {
    margin-top: 20px;
  }
</style>
