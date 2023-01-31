<template>
  <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row justify="center" class="spacer">
        <v-col cols="12" xs="12" sm="4" md="2" v-for="(category,i) in categories" :key="i">
          <v-item v-slot="{active,toggle}">
            <v-card :color="active ? 'white' : 'white'"
            :class="active ? 'borderme' : 'borderout'"
            class="d-flex align-center rounded-lg mx-2" dark height="140" flat @click="toggle">
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line class="text-center">
                    <v-list-item-content>
                      <div align="center" justify="center">
                        <v-img v-bind:src="category.img" max-height="120" max-width="120" contain></v-img>
                      </div>
                      <v-list-item-subtitle :class="active ? 'green--text' : 'black--text'"
                      class="caption mt-4">{{category.title}}</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
            </v-card>
          </v-item>
        </v-col>
      </v-row>
      <v-row justify="center" class="spacer">
        <v-col cols="12" xs="12" sm="4" md="2" v-for="(category,i) in categories" :key="i">
          <v-item v-slot="{active,toggle}">
            <v-card :color="active ? 'white' : 'white'"
                    :class="active ? 'borderme' : 'borderout'"
                    class="d-flex align-center rounded-lg mx-2" dark height="140" flat @click="toggle">
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line class="text-center">
                    <v-list-item-content>
                      <div align="center" justify="center">
                        <v-img v-bind:src="category.img" max-height="120" max-width="120" contain></v-img>
                      </div>
                      <v-list-item-subtitle :class="active ? 'green--text' : 'black--text'"
                                            class="caption mt-4">{{category.title}}</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
            </v-card>
          </v-item>
        </v-col>
      </v-row>
      <v-row justify="center" class="spacer">
        <v-col cols="12" xs="12" sm="4" md="2" v-for="(category,i) in categories" :key="i">
          <v-item v-slot="{active,toggle}">
            <v-card :color="active ? 'white' : 'white'"
                    :class="active ? 'borderme' : 'borderout'"
                    class="d-flex align-center rounded-lg mx-2" dark height="140" flat @click="toggle">
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line class="text-center">
                    <v-list-item-content>
                      <div align="center" justify="center">
                        <v-img v-bind:src="category.img" max-height="120" max-width="120" contain></v-img>
                      </div>
                      <v-list-item-subtitle :class="active ? 'green--text' : 'black--text'"
                                            class="caption mt-4">{{category.title}}</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
            </v-card>
          </v-item>
        </v-col>
      </v-row>
      <v-row justify="center" class="spacer">
        <v-col cols="12" xs="12" sm="4" md="2" v-for="(category,i) in categories" :key="i">
          <v-item v-slot="{active,toggle}">
            <v-card :color="active ? 'white' : 'white'"
                    :class="active ? 'borderme' : 'borderout'"
                    class="d-flex align-center rounded-lg mx-2" dark height="140" flat @click="toggle">
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line class="text-center">
                    <v-list-item-content>
                      <div align="center" justify="center">
                        <v-img v-bind:src="category.img" max-height="120" max-width="120" contain></v-img>
                      </div>
                      <v-list-item-subtitle :class="active ? 'green--text' : 'black--text'"
                                            class="caption mt-4">{{category.title}}</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
            </v-card>
          </v-item>
        </v-col>
      </v-row>
      <v-row justify="center" class="spacer">
        <v-col cols="12" xs="12" sm="4" md="2" v-for="(category,i) in categories" :key="i">
          <v-item v-slot="{active,toggle}">
            <v-card :color="active ? 'white' : 'white'"
                    :class="active ? 'borderme' : 'borderout'"
                    class="d-flex align-center rounded-lg mx-2" dark height="140" flat @click="toggle">
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line class="text-center">
                    <v-list-item-content>
                      <div align="center" justify="center">
                        <v-img v-bind:src="category.img" max-height="120" max-width="120" contain></v-img>
                      </div>
                      <v-list-item-subtitle :class="active ? 'green--text' : 'black--text'"
                                            class="caption mt-4">{{category.title}}</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
            </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
  </v-item-group>
</template>

<script>
export default {
  name: "CategoryComponent",
  data(){
    return{
      categories: [
        {img:require('../assets/c.jpg'),title:"first"},
        {img:require('../assets/c.jpg'),title:"first"},
        {img:require('../assets/c.jpg'),title:"first"},
        {img:require('../assets/c.jpg'),title:"first"},
        {img:require('../assets/c.jpg'),title:"first"},
        {img:require('../assets/c.jpg'),title:"first"},
      ]
    }
  }
}
</script>

<style scoped>

</style>