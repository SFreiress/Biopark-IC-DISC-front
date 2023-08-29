<template>
  <cabecalho />
  <header>
    <p>Escolha a opção com a qual você mais se identifica.</p>
  </header>
  <div>
    <Questoes />
  </div>
</template>

<script>
import Cabecalho from './components/Cabecalho.vue'
import Questoes from './components/Questoes.vue'

export default {
  name: 'App',
  components: {
    Cabecalho,
    Questoes
  }
}
</script>
