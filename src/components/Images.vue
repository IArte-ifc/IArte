<!-- NOTA: SEÇÕES COMENTADAS SERÃO FEITAS FUTURAMENTE POR QUAISQUER QUE SEJA O MOTIVO. -->
<!-- NESSA SITUAÇÃO, TÃO COMENTADAS PQ NAO CONSIGO FAZER ELAS ABRIREM EM MODAL KKKKKKKKKKK -->

<template>
  <div class="self">
    <!-- <div class="modal"></div> -->
    <img src="../assets/1.png" alt="Imagem gerada por IA">
    <img src="../assets/2.png" alt="Imagem gerada por IA">
    <img src="../assets/3.png" alt="Imagem gerada por IA">
    <img src="../assets/4.png" alt="Imagem gerada por IA">
    <img src="../assets/5.png" alt="Imagem gerada por IA">
    <img src="../assets/6.png" alt="Imagem gerada por IA">
    <img src="../assets/7.png" alt="Imagem gerada por IA">
    <img src="../assets/8.png" alt="Imagem gerada por IA">
    <img src="../assets/9.png" alt="Imagem gerada por IA">
    <img src="../assets/10.png" alt="Imagem gerada por IA">
    <img src="../assets/11.png" alt="Imagem gerada por IA">
    <img src="../assets/12.png" alt="Imagem gerada por IA">
    <img src="../assets/13.png" alt="Imagem gerada por IA">
    <img src="../assets/14.png" alt="Imagem gerada por IA">
    <img src="../assets/15.png" alt="Imagem gerada por IA">
    <img src="../assets/16.png" alt="Imagem gerada por IA">
    <img src="../assets/17.png" alt="Imagem gerada por IA">
    <img src="../assets/18.png" alt="Imagem gerada por IA">
    <img src="../assets/19.png" alt="Imagem gerada por IA">
    <img src="../assets/20.png" alt="Imagem gerada por IA">
    <img src="../assets/21.png" alt="Imagem gerada por IA">
    <img src="../assets/22.png" alt="Imagem gerada por IA">
    <img src="../assets/23.png" alt="Imagem gerada por IA">
    <img src="../assets/24.png" alt="Imagem gerada por IA">
    <img src="../assets/25.png" alt="Imagem gerada por IA">
    <img src="../assets/26.png" alt="Imagem gerada por IA">
    <img src="../assets/27.png" alt="Imagem gerada por IA">
    <img src="../assets/28.png" alt="Imagem gerada por IA">
    <img src="../assets/29.png" alt="Imagem gerada por IA">
    <img src="../assets/30.png" alt="Imagem gerada por IA">
    <img src="../assets/31.png" alt="Imagem gerada por IA">
    <img src="../assets/32.png" alt="Imagem gerada por IA">
    <img src="../assets/33.png" alt="Imagem gerada por IA">
    <img src="../assets/34.png" alt="Imagem gerada por IA">
    <img src="../assets/37.png" alt="Imagem gerada por IA">
  </div>

</template>

<script>
export default {
  name: 'appImages',
}

// var img = document.queryselector('.self img');
// function mostraModal() {

// }

// for (var i = 0; i < img.length; i++) {
//     img[i].addEventListener('click', mostraModal());
// }
</script>

<style scoped>
.self {
  padding: 7rem 0;

  img {
    width: 39%;
    margin-right: 1rem;
    margin-bottom: 1rem;
    cursor: pointer;
    transition: 0.3s;
  }

  img:hover {
    opacity: 0.7;
  }

  .modal {
    display: none; 
    position: fixed; 
    z-index: 1; 
    padding-top: 100px; 
    left: 0;
    top: 0;
    width: 100%; 
    height: 100%; 
    background-color: rgb(0,0,0); 
    background-color: rgba(0,0,0,0.9); 
  }
}

@media (max-width: 390px) {
  .self img {
    width: 80%;
    margin-bottom: 2rem;
  }
}
</style>
