<template>
  <div class="self">
    <h1>Texto teste: </h1>
    <p>Texto teste: O projeto IArte ocupou o espaço do Instituto Federal Catarinense - Campus Concórdia no ano de 2024 discutindo interativamente com o público relacionando duas ideias que parecem muito distintas, a <i>inteligência artificial</i> e a <i>arte</i>. Mas afinal, o que podemos concluir com isso? <br> O treinamento de algoritmos em grande escala usando de inúmeras formas de <i>machine learing</i> pode capacitar uma máquina a compreender de uma forma matemática, interpretá-la de forma lógica e replicá-la. Isso demora muito tempo, principalmente levando em consideração o treinamento necessário para que a IA consiga realmente agir relacionando os pontos do <i>canvas</i>. Nesse âmbito, foi-se discutido durante todo o decorrer do projeto duas principais perspectivas que podem analisar o contexto e gerar a pergunta norteadora: <br> Inteligência artificial faz arte?<br> <strong>1.</strong> A inteligência artificial não faz arte. A arte não pode ser apenas pontos no papel, mas também significa emoção, perspectiva, vida, morte. A arte é poesia, tem muito afundo, muito amor e ódio, muita vingança, sentimentos que só um ser humano é capaz de criar e expressar. <br> <strong>2.</strong> A inteligência artificial faz arte. A arte não pode ser apenas um único significado, mas sim uma metamorfose constante. Durante toda a existência humana, a arte foi um conceito que não esteve completamente firmado e completo. A arte é mudança, acima de tudo, o que torna possível que a revolução desse século seja a IArte. <br></p>
    <h1>{{ h1 }}</h1>
    <p>{{ p }}</p>
  </div>

</template>

<script>
export default {
  name: 'appTexto',
  props: {
    h1: String,
    p: String
  }
}
</script>

<style scoped>
.self {
  width: 100%;
  padding: 7rem 0;

  h1 {
    text-align: center;
  }

  p {
    font-size: 1.5rem;

  }

  strong {
    color: green;
  }
}

@media (max-width: 430px) {
  .self {
    width: 100%;
  }
}
</style>