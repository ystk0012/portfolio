<template>
  <base-card light>
    <v-img
      class="grey lighten-2"
      height="600"
      width="100%"
      :src="require('@/assets/articles/banner.jpg')"
    >
      <v-layout
        fill-height
        align-center
        pa-3
      >
        <v-flex
          xs12
          md7
          offset-md5
        >
          <h1 class="display-3">
            Yoshitaka Oitsu
          </h1>
          <div class="subheading text-uppercase pl-2 mb-4">
            It's better to regret doing something than to regret not doing it.
          </div>
        </v-flex>
      </v-layout>
    </v-img>
  </base-card>
</template>
