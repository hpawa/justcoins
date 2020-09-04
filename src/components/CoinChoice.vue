<template>
  <v-card class="pa-6">
    <v-row justify="center">
      <v-btn-toggle mandatory color="primary" multiple>
        <v-btn>GPU</v-btn>
        <v-btn>ASIC</v-btn>
        <v-btn>CPU</v-btn>
      </v-btn-toggle>
    </v-row>
    <v-row>
      <v-col>
        <v-autocomplete label="Algoritm" />
        <v-autocomplete label="Coin" />
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {}
</script>

<style></style>
