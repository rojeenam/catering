<template>
  <v-footer fixed class="font-weight-medium primary lighten-1 white--text text-end">
    <v-row>
      <v-col class="text-start">
        <strong>Follow us:</strong>
      </v-col>
      <v-col class="text-end">
        {{ new Date().getFullYear() }} —
        <strong>Araniko Catering and Rental Services</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>


<script>
export default {
  name: "Footer"
};
</script>


