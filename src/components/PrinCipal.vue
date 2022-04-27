<script>
import ArtiGo from "@/components/ArtiGo.vue";
export default {
  components: { ArtiGo },
};
</script>

<template>
  <main id="content">
    <ArtiGo titulo="Bloco1" :nomes="['Rafaela', 'Heloisa']" />
    <ArtiGo titulo="URGENTE" class="conteudo" :nomes="['Eduardo', 'Heric']" />
    <ArtiGo />
    <ArtiGo class="conteudo" />
    <ArtiGo />
    <ArtiGo class="conteudo" :nomes="['Joao']" />
  </main>
</template>

<style></style>
