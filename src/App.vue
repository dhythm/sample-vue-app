<template>
  <v-app>
    <Header />

    <v-main>
      <HelloWorld />
      <List />
    </v-main>

    <Footer />
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Header from "./components/Header";
import Footer from "./components/Footer";
import List from "./components/List";

export default {
  name: "App",

  components: {
    HelloWorld,
    Header,
    Footer,
    List,
  },

  data: () => ({
    //
  }),
};
</script>
