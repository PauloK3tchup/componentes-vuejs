<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CompRodape from "@/components/CompRodape.vue";
import CompCabecalho from "@/components/CompCabecalho.vue";
import CompConteudo from "@/components/CompConteudo.vue";
export default {
  components: {
    MenuLateral,
    CompRodape,
    CompCabecalho,
    CompConteudo,
  },
};
</script>
<template>
  <CompCabecalho />
  <MenuLateral />
  <CompConteudo />
  <CompRodape />
</template>
<style></style>
