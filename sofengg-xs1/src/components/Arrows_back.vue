<template>
  <v-tooltip top>
    <template v-slot:activator="{ on }">
      <v-btn fab color="green"
             :to="link"
             v-on="on">
        <v-icon class="primary">arrow_downward</v-icon>
      </v-btn>
    </template>
    <span>{{link}}</span>
  </v-tooltip>
</template>
<script>
  export default {
   props:['link'],
    data() {
      return {

      }
  }
}
</script>
