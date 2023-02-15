<template>
  <v-app-bar app color="white" flat>
    <v-badge color="#D5F0DB" dot>
      <v-img src="https://media.istockphoto.com/id/1206806317/tr/vekt%C3%B6r/al%C4%B1%C5%9Fveri%C5%9F-sepeti-simgesi-beyaz-arka-planda-yal%C4%B1t%C4%B1lm%C4%B1%C5%9F.jpg?s=1024x1024&w=is&k=20&c=wLda6Wc3yBLi0K3AETfB6iJ0afw0cjYeI0bzQ--8yoQ=" contain width="30"></v-img>
    </v-badge>
    <v-toolbar-title class="ml-4">
      <span class="yellow--text">ICE  </span><strong>YARNS</strong>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-badge color="#FF6D59" overlap content="2" class="mr-2 mt-1">
      <v-avatar color="#FFF0EE" size="40">
        <v-icon x-small color="FF6D59">far fa-heart</v-icon>
      </v-avatar>
    </v-badge>
    <v-badge color="#41AB55" overlap content="3" class="mr-2 mt-1">
      <v-avatar color="ECF7EE" size="40">
        <v-icon x-small color="#41AB55">fas fa-shopping-cart</v-icon>
      </v-avatar>
    </v-badge>
    <span class="grey--text d-none d-sm-flex">Hello <strong>Abbas</strong></span>
    <v-avatar size="30" class="ml-2">
      <v-img src="https://media.licdn.com/dms/image/C5603AQG0-mxpLUvsKg/profile-displayphoto-shrink_800_800/0/1539514984550?e=2147483647&v=beta&t=-grkUOIO79z1vjzXMOghgWpeLjdWIYq2CqF-MSnHg4Y"></v-img>
    </v-avatar>
    <v-btn icon dark>
      <v-icon x-small color="#878A94">fas fa-chevron-down</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: "NavbarComponent"
}
</script>

<style scoped>
.v-toolbar__title{
  font-size: 1rem !important;
}
</style>