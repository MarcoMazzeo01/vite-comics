<script>
import Header from "./components/Header.vue";

export default {
  components: {
    Header,
  },
};
</script>

<template>
  <Header />
  <main id="main_content">
    <div class="container__main">
      <h1 class="text-white">TEST</h1>
    </div>
  </main>
</template>

<style lang="scss">
#main_content {
  background-color: #1c1c1c;
  min-height: 200px;

  .container__main {
    margin: auto;
    width: 90%;
    padding: 2em 0;
  }
}

#menu_list {
  display: flex;

  li {
    list-style: none;
  }
}
</style>
