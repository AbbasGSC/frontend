<template>
  <v-app>
    <NavbarComponent/>
    <v-container fluid>
      <SlideComponent/>
      <CategoryComponent/>
      <ProductComponent/>
      <FooterComponent/>
    </v-container>

  </v-app>
</template>

<script>
// @ is an alias to /src

import NavbarComponent from "@/components/NavbarComponent.vue";
import CategoryComponent from "@/components/CategoryComponent.vue";
import SlideComponent from "@/components/SlideComponent.vue";
import ProductComponent from "@/components/ProductComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";

export default {
  name: 'HomeView',
  components: {
    FooterComponent,
    ProductComponent,
    SlideComponent,
    CategoryComponent,
    NavbarComponent,
  }
}
</script>
<style>

</style>