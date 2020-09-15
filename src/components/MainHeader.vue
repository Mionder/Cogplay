<template>
  <div class="header">
      <div class="header__container _container">
            <div class="header__menu menu">
            <a class="header__logo" href="#"><img src="img/logo1.svg" alt="logo"></a>
            <nav class="menu__body">
                <ul class="menu__list">
                    
                    <li><router-link :to="'/'" class="menu__link">Home</router-link></li>
                    <li><router-link :to="'/pricing'" class="menu__link">Pricing</router-link></li>
                    <li><router-link :to="'/pricing'" class="menu__link">Choose pricing plan </router-link></li>
                </ul>
            </nav>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style  lang="scss" scoped>
  
</style>
