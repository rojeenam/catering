<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <span class="mr-2 icon font-italic font-weight-medium">A</span>
      </div>

      <v-spacer></v-spacer>

      <v-col class="justify-end">
        <v-row class="justify-end">
          <span>Araniko Catering & Rental Services</span>
        </v-row>
        <v-row class="justify-end">
          <span>984-1247156</span>
        </v-row>
      </v-col>
    </v-app-bar>

    <v-content>
      <Slider/>
      <v-row class="ma-5">
        <v-col cols="3">
          <About/>
        </v-col>
        <v-col cols="6">Body</v-col>
        <v-col cols="3">
          <Contact/>
        </v-col>
      </v-row>
    </v-content>
    <Footer/>
  </v-app>
</template>

<script>
import Slider from "./components/Slider";
import About from "./components/About";
import Contact from "./components/Contact";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Slider,
    About,
    Contact,
    Footer
  },

  data: () => ({
    //
  })
};
</script>

<style lang="css" scoped>
.icon {
  color: white;
  font-size: 40px;
}
</style>
