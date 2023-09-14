<script>
console.log("WHAT");
</script>

<template>
  <header class="container-fluid mx-auto p-0 bg-success">
    <div class="container d-flex justify-content-around p-0 bg-warning">
      <div id="logo">
        <img src="\img\dc-logo.png" alt="dc_logo" />
      </div>

      <div>
        <ul id="menu_list" class="mb-0">
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Fans</li>
          <li>News</li>
          <li>Shop</li>
        </ul>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  height: 150px;

  .container {
    height: 100%;
  }
}

#logo {
  width: 125px;
  aspect-ratio: 1;
  display: flex;
  align-items: center;

  img {
    width: 100%;
  }
}

#menu_list {
  gap: 10px;
  height: 100%;

  li {
    display: inline-block;
    height: 100%;
    border-bottom: 10px $accent-color solid;
    font-family: none;
  }
}
</style>
