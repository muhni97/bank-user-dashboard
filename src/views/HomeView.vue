<template>
  <v-app id="inspire" :style="{background : $vuetify.theme.themes.dark.background}">
  <SideBar />
  <v-container>
    <NavBar />
    <v-row>
      <v-col cols="12" sm="8">
        <v-row>
          <v-col cols="12" sm="12">
            <OverView />
          </v-col>
          <v-col cols="12" sm="12">
            <MoneySection />
          </v-col>
          <v-col cols="12" sm="12">
            <PaymentSection />
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" sm="4">
        <CardSection />
      </v-col>
    </v-row>
  </v-container>
  </v-app>
</template>

<script>
import SideBar from '@/components/SideBar.vue';
import NavBar from '@/components/NavBar.vue';
import OverView from '@/components/OverView.vue';
import PaymentSection from '@/components/PaymentSection.vue';
import CardSection from '@/components/CardSection.vue';
import MoneySection from '@/components/MoneySection.vue';

  export default {
    name: 'HomeView',
    components: {
    SideBar,
    NavBar,
    OverView,
    MoneySection,
    PaymentSection,
    CardSection,
},
  }
</script>

<style scoped>

.v-btn-withoutuppercase{
  text-transform: none !important;
}
.v-btn:not(.v-btn--round).v-size--small{
  min-width: 30px !important;
  padding: 0 5px !important;
}

</style>
