<template>
  <div>
    <Header />
  </div>
  <div>
    <lotto_body />
  </div>
  
  참고 :   <a href="https://jssvs.tistory.com/">데이터 엔지니어 기술 블로그</a>
</template>

<script>
import Header from '@/components/layout/Header.vue'
import lotto_body from '@/components/layout/Body.vue'
export default {
  components : {
    Header,
    lotto_body,
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
