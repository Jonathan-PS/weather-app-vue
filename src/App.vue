<template>
  <v-app>
    <v-content>
      <!--<HelloWorld/>-->
      <TheMap/>
    </v-content>
  </v-app>
</template>

<script>
import TheMap from "./components/TheMap";

export default {
  name: "App",
  components: {
    TheMap
  },
  data() {
    return {
      drawer: null
    };
  }
};
</script>


<style>
</style>