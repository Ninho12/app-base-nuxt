<template>
  <div>
    <MenuPrincipal />

    <Hero/>
    <Beneficios />

    <FooterPrincipal />
  </div>
</template>

<script>
import Beneficios from '../components/partes/beneficios.vue';
import FooterPrincipal from '../components/partes/footer-principal.vue';
import Hero from '../components/partes/hero.vue';
import MenuPrincipal from '../components/partes/menu-principal.vue';


export default {
    name: "IndexPage",
    components: { MenuPrincipal, Hero, FooterPrincipal, Beneficios }
}

</script>
