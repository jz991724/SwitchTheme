<template>
  <div class="home">
<!--    <img alt="Vue logo" src="../assets/logo.png" />-->
<!--    <HelloWorld msg="Welcome to Your Vue.js App" />-->
    <hello-vue></hello-vue>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import HelloVue from "@/components/HelloVue";

export default {
  name: "home",
  components: {
    // HelloWorld,
    HelloVue
  }
};
</script>
