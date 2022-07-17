<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
  mounted() {
    // this.init();
  },
  methods: {
    // init() {
    //   setTimeout(() => {
    //     console.log(145);
    //     setTimeout(() => {
    //       console.log(2);
    //       setTimeout(() => {
    //         console.log(3);
    //       }, 1000);
    //     }, 1000);
    //   }, 1000);
    // },
  },
};
</script>
