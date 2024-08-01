<script setup>
const nome = "priscilla b"
const meuObj = {
  nome: "priscilla",
  serieFavorita: "Game of Thrones"
}

function dizOla(nome) {
  return `${nome} diz oi`;
}

const enderecoDaImagemDoDragao = "https://tm.ibxk.com.br/2024/07/16/16112748460102.jpg?ims=750x"
const botaoEstaDesabilitado = false

const gostaDoDragao = false

</script>



<template>
  <h1>{{ dizOla("Paula") }}</h1>
  <img v-show="gostaDoDragao" :src="enderecoDaImagemDoDragao">

  <button :disabled="!botaoEstaDesabilitado">enviar mensagem</button>

</template>

<style scoped>

</style>
