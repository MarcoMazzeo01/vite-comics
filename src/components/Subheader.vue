<script></script>

<template>
  <header>
    <ul class="menu_list mb-0">
      <li>
        <img src="/img/buy-comics-digital-comics.png" alt="comics" />
        <h2>Digital Comics</h2>
      </li>
      <li>
        <img src="/img/buy-comics-merchandise.png" alt="comics" />
        <h2>DC Merchandise</h2>
      </li>
      <li>
        <img src="/img/buy-comics-subscriptions.png" alt="comics" />
        <h2>Subscriptions</h2>
      </li>
      <li>
        <img src="/img/buy-comics-shop-locator.png" alt="comics" />
        <h2>Comics Shop Locator</h2>
      </li>
      <li>
        <img src="/img/buy-dc-power-visa.svg" alt="comics" />
        <h2>DC Power Visa</h2>
      </li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: $accent-color;
  min-height: 10px;
}

.menu_list {
  display: flex;
  justify-content: center;
  gap: 50px;
  padding: 2em 0;

  li {
    display: flex;
    align-items: center;
    gap: 15px;
    color: white;
    text-transform: uppercase;
    font-family: $menu-font;

    h2 {
      font-size: 1.3em;
    }
    img {
      width: 50px;
    }
  }
}
</style>
