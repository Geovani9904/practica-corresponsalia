<template>
  <v-container class="fill-height">
    <v-responsive class="aling-center text-center fill-height">
  <v-layout aling-center justify-center>
    <v-flex xs12 sm8 md4>
      <v-card class="elevation-100" height="300px" width="460px" >
        <v-toolbar dark color="green">
        <v-toolbar-title>Login</v-toolbar-title>
      </v-toolbar>
      <v-card-text>
        <v-form>
          <v-text-field
          prepend-icon="person"
          name="login"
          label="login"
          id="login"
          type="text"
          ></v-text-field>
          <v-text-field
          prepend-icon="lock"
          name="password"
          label="Password"
          id="password"
          type="password"
          ></v-text-field>
        </v-form>
      </v-card-text>
      <v-card-actions>
        <v-spacer></v-spacer>
          <v-btn dark color="black"></v-btn>
      </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
    </v-responsive>
</v-container>
</template>

<script setup>
  //
</script>
