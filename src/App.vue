<template>
  <v-app dark>
    <!--    Input my contests    -->
    <v-content>
      <Header />
      <Top />
      <Footer />
    </v-content>
  </v-app>
</template>

<script>

import Top from "./components/Top";
import Header from "./components/Header";
import Footer from "./components/Footer";
// import Works from "./components/Works";
// import TopPage from "./components/TopPage";

export default {
  name: "App",
  components: {
    // TopPage,
    Header,
    Top,
    Footer,

    // Works,
  },
  icons: {
    iconfont: "mdi", // default - only for display purposes
  },
};
</script>
