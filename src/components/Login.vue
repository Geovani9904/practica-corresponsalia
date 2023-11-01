<template>
  <v-layout align-center justify-center>
    <v-flex xs12 sm8 md4>
      <v-sheet outlined color="#00953B" rounded>
      <v-card class="elevation-40" width="450px" height="500">
        <v-toolbar dark color="green">
          <v-toolbar-title>Inicio de sesion</v-toolbar-title>
        </v-toolbar>
        <v-card-text>
          <v-form>
            <v-text-field
              name="Correo electronico"
              label="Correo electronico"
              id="Correo-electronico"
              type="text"
            ></v-text-field>
            <v-text-field
              name="Contraseña"
              label="ontraseña"
              id="ontraseña"
              type="ontraseña"
            ></v-text-field>
          </v-form>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn id="buton-can">Cancelar</v-btn>
          <v-btn id="buton-con">Continuar</v-btn>
        </v-card-actions>
      </v-card>
    </v-sheet>
    </v-flex>
  </v-layout>
</template>

<style>
#buton-can{
  background-color: white;
  color: #00953B;
  border-radius: 20px;
}

#buton-con{
  background-color: white;
  color: #00953B;
}
#Correo-electronico{
background-color: white;
color: #00953B;
border-block-start-color: #00953B;
border-radius: 10px;
width: 452px;
height: 77px;
border: 1px;
padding: 0px, 25px, 0px, 25px;
gap: 10px;
}
</style>
