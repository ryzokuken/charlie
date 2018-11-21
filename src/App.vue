<template>
  <div>
    <Navbar />
    <div class="container">
      <Header />
      <MainForm />
      <b-card-group deck id="content">
        <Article v-for="(article, index) in articles" :key="index"/>
      </b-card-group>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import MainForm from './components/MainForm.vue'
import Article from './components/Article.vue'

export default {
  name: 'charlie',
  components: {
    Navbar,
    Header,
    MainForm,
    Article
  },
  data() {
    return {
      articles: new Array(8)
    };
  }
}
</script>

<style scoped>
  #content {
    margin-top: 20px;
  }
</style>
