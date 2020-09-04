<template>
  <v-row>
    <v-col cols="12">
      <v-row justify="center" class="grey lighten-5" style="height: 300px;">
        <coin-choice />
      </v-row>
    </v-col>
  </v-row>
</template>

<script>
import CoinChoice from "../components/CoinChoice.vue"
export default {
  components: {
    CoinChoice
  }
}
</script>

<style></style>
