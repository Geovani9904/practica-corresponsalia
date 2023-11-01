<template>
  <v-container >
    <v-layout>
      <!-- <HelloWorld /> -->
      <h1>Home</h1>
    </v-layout>
    <Login class="mt-9" style="margin: 290px;"/>
  </v-container>
</template>

<script >
  // import HelloWorld from '@/components/HelloWorld.vue'
  import Login from "../components/Login.vue";

  export default {
    components: {
      Login
    }
  };
</script>
