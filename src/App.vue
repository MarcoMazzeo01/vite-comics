<script>
import Header from "./components/Header.vue";
import Subheader from "./components/Subheader.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Header,
    Subheader,
    Footer,
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
  <Subheader />
  <Footer />
</template>

<style lang="scss">
#main_content {
  background-color: #1c1c1c;
  min-height: 200px;
}

.container__main {
  margin: auto;
  width: 90%;
  padding: 2em 0;
}

.menu_list {
  display: flex;

  li {
    list-style: none;
  }
}
</style>
