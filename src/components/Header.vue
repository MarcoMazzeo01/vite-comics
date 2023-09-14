<script></script>

<template>
  <header class="container-fluid bg-white">
    <div class="container d-flex justify-content-around p-0">
      <div id="logo">
        <img src="\img\dc-logo.png" alt="dc_logo" />
      </div>

      <div>
        <ul class="menu_list mb-0">
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
  height: 120px;
  padding: 10px 0;

  .container {
    height: 100%;
  }
}

#logo {
  width: 103px;
  aspect-ratio: 1;
  display: flex;
  align-items: center;

  img {
    width: 100%;
  }
}

.menu_list {
  gap: 20px;
  height: 100%;
  font-family: $menu-font;
  color: #4a4a4a;

  li {
    display: inline-block;
    background-color: white;
    height: 100%;
    border-bottom: 0px $accent-color solid;
    display: flex;
    align-items: center;
    text-transform: uppercase;
  }

  li:hover {
    animation-name: borderGrow;
    animation-fill-mode: forwards;
    animation-duration: 0.2s;
  }

  @keyframes borderGrow {
    from {
      border-bottom: 0px $accent-color solid;
    }
    to {
      border-bottom: 6px $accent-color solid;
    }
  }
}
</style>
