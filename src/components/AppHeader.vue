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
    <div class="container">
      <div class="row">
        <img src="" alt="img logo" />
        <h1>Yu-Gi-Ho API</h1>
      </div>
    </div>
  </header>
</template>

<style></style>
