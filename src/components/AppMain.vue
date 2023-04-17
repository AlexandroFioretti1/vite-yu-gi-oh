<script>
import { store } from "../assets/data/store";
import CardList from "./CardList.vue";

export default {
  name: "AppMain",
  components: {
    CardList,
  },
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <main>
    <div class="container">
      <CardList />
    </div>
  </main>
</template>

<style lang="scss">
main {
  background-color: #d58f39;
}
.bg_dark {
  color: white;
  background-color: #212428;
}
.container {
  background-color: #ffff;
}

</style>
