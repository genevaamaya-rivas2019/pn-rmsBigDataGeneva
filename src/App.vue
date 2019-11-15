<template>
  <v-content>
    <Dashboard />
    <Header />
  </v-content>
</template>

<script>
import Dashboard from "./components/Dashboard";
import Header from "./components/Header";

export default {
  name: "App",
  components: {
    Dashboard,
    Header
  },

  data: () => ({
    //
  })
};
</script>
