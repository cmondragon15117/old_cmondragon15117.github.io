<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Main msg="Crista Mondragon's Portfolio" />
  </div>
</template>

<script>
// @ is an alias to /src
import Main from "@/components/Main.vue";
import Sidebar from "@/components/Sidebar.vue";
export default {
  name: "home",
  components: {
    Main,
    Sidebar
  }
};
</script>
