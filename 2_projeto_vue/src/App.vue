<template>
  <PrimeiroComponente />
</template>

<script setup>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';
/*  Obs: Não é mais necessário usar o export default, basta colocar o "setup" dentro da tag script: <script setup> :

 export default {                
    name: 'App',
    components: {
      PrimeiroComponente
    }
  }
*/
</script>