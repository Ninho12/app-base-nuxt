<template>
    
    <div>
        <MenuPrincipal />


        <FooterPrincipal />
    </div>


</template>

<script>
import FooterPrincipal from '../components/partes/footer-principal.vue';
import MenuPrincipal from '../components/partes/menu-principal.vue';

export default {
    name: "Politica",
    components: { FooterPrincipal, MenuPrincipal }
}

</script>