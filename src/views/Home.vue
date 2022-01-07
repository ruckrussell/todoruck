<template>
<div class="home">
  <h1>¡Hola vue! uwu</h1>
 <v-btn class="pink white--text">Click me</v-btn> 
 <v-btn depressed dark color="pink">click me</v-btn>
 <v-btn text color="pink">click me</v-btn>

 <v-btn depressed class="pink white--text">
   <v-icon left>mdi-email</v-icon>
   <span>email me</span>
 </v-btn>

 <v-btn depressed large class="pink white--text">
   <span>email me</span>
   <v-icon large rigth>mdi-email</v-icon>
 </v-btn>

 <v-btn fab depressed small dark color="purple">
   <v-icon>mdi-heart</v-icon>
 </v-btn>

</div>
</template>

<script>

  export default {
    name: 'Home',

    components: {
    },
  }
</script>
