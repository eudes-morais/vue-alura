<!-- Pode-se dizer que é o componente raíz de toda a aplicação -->
<!-- Isto é um single file component (template + css)-->

<script lang="ts">
import Banner from './components/Banner.vue';

export default {
  components: { Banner: Banner }
  // ou components: { Banner } (As duas maneiras de escrever o componente estão certas)
}
</script>

<template>
  <Banner />
</template>

<style scoped>

</style>