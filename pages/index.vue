<template>
  <div>
    <v-row>
      <h1 class="mx-auto">Margin</h1>
    </v-row>
    <v-card class="mt-5 mb-8">
      <v-card-text>
        ml - mt - mr - mb: margin-left- top - right- bottom
        <br />
        mx -my: margin-left and right - margin-top and bottom
        <br />
        ma: magin all
      </v-card-text>
    </v-card>
    <v-row>
      <h1 class="mx-auto">Button</h1>
    </v-row>
    <v-row>
      <v-col>
        <v-btn fab>
          <v-icon>mdi-pencil</v-icon>
        </v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-btn>normal</v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-btn tile>tile (button vuông ở góc)</v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-btn outlined>outlined</v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <button v-ripple class="elevation-2 px-4 green">html button with press effect</button>
      </v-col>
    </v-row>
  </div>
</template>
