<template>
  <section>
    <h1>Rutas con Vue Router</h1>
    <router-link to="/" exact>Home</router-link>
    <router-link to="/contacto">Contacto</router-link>
    <router-link to="/usuario/77">Usuario</router-link>
    <router-link to="/usuario/99">Usuario</router-link>
    
    <hr>
    <router-view></router-view>
  </section>
</template>

<script>
export default {
}
</script>

<style>
  .router-link-active{
    color:red;
  }
</style>
