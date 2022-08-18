<template>
  <v-app-bar color="transparent" flat class="mt-2">
    <div>
      <h4 class="white--text mt-n3">Design Expert</h4>
      <br />
      <p class="grey--text caption mt-n5">Let's manage your data now!</p>
    </div>
    <v-text-field
      label="Search..."
      fillied
      prepend-inner-icon="mdi-magnify"
      dense
      solo
      flat
      background-color="#1d1c21"
      dark
      class="ml-5"
    ></v-text-field>
    <v-spacer></v-spacer>
    <v-icon color="#878a94" class="mt-n8">far fa-envelope</v-icon>
    <v-badge
      bordered
      overlap
      color="red"
      content="2"
      class="ml-3 mt-n8"
      dark
    >
    <v-icon color="#878a84">far fa-bell</v-icon>
    </v-badge>
    <v-avatar size="30" class="ml-3 mt-n8">
      <v-img src="@/assets/image1.jpg"></v-img>
    </v-avatar>
    <div>
      <p class="white--text mt-n3 ml-2 caption">Mustafa Sarıgöl</p><br>
      <p class="grey--text mt-n10 ml-2 caption">Sakarya, Turkey</p>
    </div>
    <v-icon x-small color="#878a94" class="mt-n8 ml-2">fas fa-chevron-down</v-icon>
  </v-app-bar>
</template>

<script>
export default {};
</script>

<style>
</style>