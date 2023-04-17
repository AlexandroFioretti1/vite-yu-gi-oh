<script>
export default {
  name: "InfoCard",
  props: {
    card: Object,
  },
};
</script>

<template>
  <div class="col">
    <div class="card text-center">
      <img
        class="img-fluid"
        :src="card.card_images[0].image_url"
        :alt="card.name"
      />
      <div class="title">
        <h5>{{ card.name }}</h5>
      </div>
    </div>
  </div>
</template>

<style lang="scss"></style>
