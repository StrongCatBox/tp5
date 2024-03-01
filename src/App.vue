<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    
    <div class="wrapper">
      
      
      
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
        <ul class="navbar-nav">
          

            <RouterLink class=' navbar-brand' to="/">Home</RouterLink>
          

          
        <RouterLink class="nav-link" to="/products/list">Nos produits</RouterLink>
    
      </ul>
      </nav>

    </div>
  </header>

  <RouterView />
</template>

<style scoped>


</style>
