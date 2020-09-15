<template>
  <div id="app">
    <MainPage />
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'

export default {
  name: 'App',
  components: {
    MainPage
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

#app {
 font-family: 'Poppins', sans-serif;
}

/* ._container */

._container{
   max-width: 1266px;
    margin: 0 auto;
}

@media screen and (max-width: 1440px){
    ._container{
        width: 85%;
    }
}
</style>
