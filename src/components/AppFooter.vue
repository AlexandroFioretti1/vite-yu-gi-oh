<script>
import { store } from "../assets/data/store";

export default {
  name: "AppFooter",
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <footer>
    <section>
      <div class="container text-center">
        <span> &copy; copiryght by Alexandro Fioretti</span>
      </div>
    </section>
  </footer>
</template>

<style lang="scss">
footer {
  background-color: #d58f39;
}
</style>
