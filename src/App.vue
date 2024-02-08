<template>
<body>
  <Header> </Header>
  <Main></Main>
  <Footer></Footer>
</body>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
    name: 'App',
    components: {
      Header,
      Main,
      Footer
    }
  }
</script>

<style>
body {
    font-family: 'Verdana', sans-serif;
    line-height: 1.5;
    margin: 0;
}
</style>
