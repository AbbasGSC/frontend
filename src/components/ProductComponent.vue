<template>
<v-row justify="center" class="space px-16">
  <v-col cols="12" xs="12" sm="6" md="3" v-for="(product,i) in products" :key="i">
    <v-card class="mx-auto rounded-x1" max-width="300" flat outlined>
       <div align="center" justify="center">
         <v-img max-height="300" max-width="300" contain :src="product.img"></v-img>
       </div>
      <v-card-title>{{product.title}}</v-card-title>
      <v-card-title class="grey--text text-grey-darken-1 caption mt-n6">{{product.subtitle}}</v-card-title>
      <v-card-title class="mt-4">{{product.price}}</v-card-title>
      <v-card-actions class="mw-2 mt-n4">
        <v-btn class="mt-n2 add" outlined>
          <v-icon color="green" @click="product.bpm--">mdi-minus</v-icon>
        </v-btn>
        <strong class="mx-2">{{product.bpm}}</strong>
        <v-btn class="mt-n2 add" outlined>
          <v-icon color="green" @click="product.bpm++">mdi-plus</v-icon>
        </v-btn>
        <v-spacer></v-spacer>
        <v-btn class="mx-2 mt-n3" fab dark small color="green">
          <v-icon dark> mdi-shopping </v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>
  </v-col>
</v-row>
</template>

<script>
export default {
  name: "ProductComponent",
  data(){
    return{
      products:[
        {img:require('../assets/c.jpg'),title:"ice yarns 1",subtitle:"gsc tekstil",price:"10$", bpm:1},
        {img:require('../assets/c.jpg'),title:"ice yarns 2",subtitle:"gsc tekstil",price:"11$", bpm:1},
        {img:require('../assets/c.jpg'),title:"ice yarns 3",subtitle:"gsc tekstil",price:"12$", bpm:1},
        {img:require('../assets/c.jpg'),title:"ice yarns 4",subtitle:"gsc tekstil",price:"14$", bpm:1},
        {img:require('../assets/c.jpg'),title:"ice yarns 5",subtitle:"gsc tekstil",price:"15$", bpm:1},
        {img:require('../assets/c.jpg'),title:"ice yarns 6",subtitle:"gsc tekstil",price:"17$", bpm:1},
      ]
    }
  },
  methods:{
    decrement(){
      this.products.bpm++;
    },
    increment(){
      this.products.bpm++;
    }
  }
}
</script>

<style scoped>

</style>