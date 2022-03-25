<template>
  <div class="pasteleria">
    <img alt="pasteleria logo" src="../assets/Pasteleria.png" >
  </div>
  <ContenidoInicio/>
</template>

<script>
// @ is an alias to /src
import ContenidoInicio from "../components/ContenidoInicio.vue";

export default {
  name: 'HomeView',
  components: {
    ContenidoInicio,
  },
}
</script>

<style>

  body{
    background-color: #e9dfb9;
  }

  .pasteleria{
    position: relative;
    top: 15px;
  }

  .pasteleria img{
    position: relative;
    width: 150px;
    border-radius: 5px;
  }

</style>
