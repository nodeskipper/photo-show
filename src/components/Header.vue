<template>
  <v-container>
    <v-toolbar flat>

      <v-toolbar-title>Photo-show</v-toolbar-title>

      <v-spacer></v-spacer>
      
      <v-toolbar-items>
        <v-btn text>
          <router-link to="/">Home</router-link>
        </v-btn>

        <v-btn text>
          <router-link to="/about">About</router-link>
        </v-btn>

        <v-btn text>
          <router-link to="/contact">Contact</router-link>        
        </v-btn>
      </v-toolbar-items>
      
    </v-toolbar>
  </v-container>
</template>

<script>
export default {
  name: 'Header',
  data(){
      return{
        
      }
  }
}
</script>
