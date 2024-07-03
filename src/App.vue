<script setup lang="ts">
import { ref } from "vue";

const title = ref("title");
</script>

<template>
  <v-app>
    <v-main>
      <v-container>
        <v-text-field v-model="title"></v-text-field>
        <v-card :title></v-card>
      </v-container>
    </v-main>
  </v-app>
</template>
