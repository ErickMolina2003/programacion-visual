<template>
  <div class="main-container">
    <v-container class="fill-height">
      <v-row>
        <v-col class="text-center" lg="3" md="3" cols="12">
            <v-card class="mx-auto operation-card" height="250" width="250">
              <v-row justify="center" class="operation-container">
                <v-col class="pt-0" cols="6" md="4" lg="4" align-self="center">
                  <h1>+</h1>
                </v-col>
              </v-row>
            </v-card>
        </v-col>
        <v-col class="text-center" lg="3" md="3" cols="12">
            <v-card class="mx-auto operation-card" height="250" width="250">
              <v-row justify="center" class="operation-container">
                <v-col class="pt-0" cols="6" md="4" lg="4" align-self="center">
                  <h1>-</h1>
                </v-col>
              </v-row>
            </v-card>
        </v-col>
        <v-col class="text-center" lg="3" md="3" cols="12">
            <v-card class="mx-auto operation-card" height="250" width="250">
              <v-row justify="center" class="operation-container">
                <v-col class="pt-0" cols="6" md="4" lg="4" align-self="center">
                  <h1>*</h1>
                </v-col>
              </v-row>
            </v-card>
        </v-col>
        <v-col class="text-center" lg="3" md="3" cols="12">
            <v-card class="mx-auto operation-card" height="250" width="250">
              <v-row justify="center" class="operation-container">
                <v-col class="pt-0" cols="6" md="4" lg="4" align-self="center">
                  <h1>/</h1>
                </v-col>
              </v-row>
            </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import { Component } from "vue-property-decorator";

@Component({
  name: "MainOperations",
})
export default class MainOperations extends Vue {}
</script>

<style scoped>
.main-container {
  height: 100%;
  background-color: rgb(128, 234, 128) !important;
}

.operation-container {
  height: 100%;
}

.operation-card {
    cursor: pointer;
}
</style>
