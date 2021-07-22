<template>
  <div>
    <h1>grid system</h1>
    <h3>place inside v-container to use flex effect</h3>
    <v-container pa-15>
      <v-row>
        <v-col sm="4" offset-sm="4"> offset-sm: place v-col to certain offset. (Resize browser) </v-col>
      </v-row>
      <v-row>
        <v-col cols="4"> col1 </v-col>
        <v-col cols="4"> col2 </v-col>
        <v-col cols="4"> col3 </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  border: 1px solid green;
}
.row {
  border: 1px solid red;
}
.col {
  border: 1px solid blue;
}
</style>