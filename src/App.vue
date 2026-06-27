<script setup></script>

<template>
  <v-app>
    <v-app-bar>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <router-link to="/" class="text-h6 text-decoration-none">
        <v-app-bar-title>Template Vue</v-app-bar-title>
      </router-link>
      <v-spacer></v-spacer>
      <v-btn
        to="/about"
        variant="text"
        text="About"
        ></v-btn
      >
    </v-app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>
