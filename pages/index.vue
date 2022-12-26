<template>
  <div>

    <Header/>
    <BeneficiosSimples/>

  </div>
</template>

<script>
import BeneficiosSimples from '../components/principal/beneficios-simples.vue';
import Header from '../components/principal/header.vue';



export default {
    name: "IndexPage",
    components: { Header, BeneficiosSimples }
}

</script>
