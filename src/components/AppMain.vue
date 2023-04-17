<script>
import { store } from "../assets/data/store";

export default {
  name: "AppMain",
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
      <div class="row">
        <h2 class="bg_dark">found ** Cards</h2>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
        <div class="card">
          <img src="" alt="img" />
          <div class="title">description</div>
          <span>description</span>
        </div>
      </div>
    </div>
  </main>
</template>

<style lang="scss">
main {
  background-color: #d58f39;
  height: 500px;
}
.bg_dark {
  color: white;
  background-color: #212428;
}
.container {
  background-color: #ffff;
}
.card {
  width: calc(90% / 5);
  margin: auto;
}
</style>
