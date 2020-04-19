<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Bienvenido a tuki
        
        </h1>

        <p class="subheading font-weight-regular">
          Proximamente disponible
          <br>Ingresen a nuestra gran comunidad 
          <a
            href="https://www.facebook.com/Tukiviajes/"
            target="_blank"
          >Facebook</a>
        </p>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Qué Sigue?
        </h2>

        <v-row justify="center">
          <a
            v-for="(next, i) in whatsNext"
            :key="i"
            :href="next.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ next.text }}
          </a>
        </v-row>
      </v-col>


      <v-col
        class="mb-5"
        cols="12"
      >
      
      <template>
  <v-parallax
    height="300"
    src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"
  ></v-parallax>
</template>

      
      </v-col>
    </v-row>
  </v-container>
</template>

