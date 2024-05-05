<template>
  <v-app>
    <v-btn @click="toggleTheme()">toggle theme</v-btn>
    ...
    <v-card theme="dark">
      <!-- button uses dark theme -->
      <v-btn>foo</v-btn>
    </v-card>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script setup>
import { useTheme } from "vuetify";

const theme = useTheme();

function toggleTheme() {
  theme.global.name = theme.global.current.dark ? "light" : "dark";
  console.log("hellow");
}
</script>
