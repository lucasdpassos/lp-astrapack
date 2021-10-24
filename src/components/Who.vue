<template>
  <div style="background-color:black;display:flex;flex-direction:column;justify-content:center;align-items:center;height:700px;">   

      <p class="roadTitle">Quem somos nós?</p>

        <div style="display:flex;flex-direction:row;justify-content:center;">
       <v-img style="max-width:500px;" src="../assets/astra-logo.png" />     

       <div style="margin:100px;display:flex;flex-direction:column"> 
       <p class="whoTitle">A <b>Astrapack</b> é uma madtech formada por apaixonados em tecnologia,<br />
       por isso, nosso time de especialistas une os poderes de marketing, advertising <br /> e engenharia, para proporcionar um <b>boost</b> gigantesco na venda e na <br />
       retenção de leads dos nossos parceiros, ao mesmo tempo que moderniza as<br /> operações com tecnologia de ponta. Nós trabalhamos em cima de toda <br /> a 
       esteira dos seus Leads, começando pela criação das campanhas, <br/> passando pelos assistentes virtuais, até o fechamento da venda.
       </p>
       <v-btn>Baixar Apresentação</v-btn>
       </div>
       </div>

  </div>
</template>

<script>
 

  export default {
    name: 'Banner',

    components: {
      //
    },
  }
</script>


<style lang="scss">
@import './src/sass/variables.scss';

.whoTitle {
    font-size: 20px;
    font-family: $subtitle-font-family;
    font-weight: 100;
    text-align: center;
}


</style>