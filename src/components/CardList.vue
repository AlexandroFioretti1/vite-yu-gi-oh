<script>
import { store } from "../assets/data/store";
import InfoCard from "../components/InfoCard.vue";

export default {
  name: "CardList",
  components: {
    InfoCard,
  },
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <div class="row row-cols-lg-5 row-cols-md-3">
    <InfoCard :card="card" v-for="card in store.cards" v-if="!store.loading" />
    <div v-else class="loading">Loading...</div>
  </div>
</template>

<style lang="scss"></style>
