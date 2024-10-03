<!-- Pode-se dizer que é o componente raíz de toda a aplicação -->
<!-- Isto é um single file component (template + css)-->

<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

export default {
  components: { Banner: Banner, ConteudoPrincipal }
  // ou components: { Banner } (esta é a outro maneira de escrever o componente, já que a chave/valor são os mesmos)
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
</template>

<!-- O SCOPED abaixo referenciado, serve atribuir um ID para os elementos que estão no script, não afetando outros componentes -->
 <!-- Caso a tag STYLE não tenha o scoped, todos os demais componentes da aplicação serão afetados pelo style globalmente -->
<style scoped>

</style>