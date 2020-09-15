<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
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
        width: 80%;
    }
}

@media screen and (max-width: 1140px){
    ._container {
      width: 64%;
    }
}

</style>
