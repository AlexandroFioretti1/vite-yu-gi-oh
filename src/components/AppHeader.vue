<script>
import { store } from "../assets/data/store";

export default {
  name: "AppHeader",
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <header>
    <div class="container_full">
      <h1>Yu-Gi-Ho API</h1>
    </div>
  </header>
</template>

<style lang="scss">
header {
  background-color: #d58f39;
  padding: 0 0 3rem 0;
}
.container_full {
  width: 100%;
  background-color: #ffff;
}
h1 {
  padding-left: 10rem;
}
</style>
