<template>
  <div class="lottogene-top">
    <Header/>
  </div>
  <div class="lottogene-middle">
    <Container/>
  </div>
  <div class="lottogene-bottom">
    <Footer/>
  </div>

</template>

<script>
import '@/assets/style.css'
import Container from '@/components/layout/Container.vue'
import Header from '@/components/layout/Header.vue'
import Footer from './components/layout/Footer.vue'

export default {
  name: "app",
  components : {
    Container,
    Header,
    Footer
  }
}

</script>

<style>
.lottogene-top {
    background-color: blanchedalmond;
    height: 10%;
}
.lottogene-middle  {
    background-color: blanchedalmond;
    height: 50vw;
}


.lottogene-bottom  {
    background-color: blanchedalmond;
    height: 10vw;
}
</style>
