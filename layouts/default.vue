<template>
  <v-app>
    <v-content>
      <v-toolbar
        dark
        prominent
        flat
        height="500"
        src="/learnenglish/img/header.png"
      >
        <v-img
          max-width="140"
          src="/learnenglish/img/puzzle.png"
        ></v-img>
        <v-toolbar-title>Курс английского языка, работающий на 100% КПД</v-toolbar-title>
      </v-toolbar>

      <v-container fluid>
        <nuxt />
      </v-container>
    </v-content>
  </v-app>
</template>