<script></script>

<template>
  <footer>
    <div class="top__footer">
      <div class="container__main">
        <div class="row">
          <div class="col-2">
            <h3>DC Comics</h3>
            <ul>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
            <h3>Shop</h3>
            <ul>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </div>
          <div class="col-2">
            <h3>DC</h3>
            <ul>
              <li>Terms Of Use</li>
              <li>Privacy policy (new)</li>
              <li>Ad Choices</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshop</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contact Us</li>
            </ul>
          </div>
          <div class="col-2">
            <h3>Sites</h3>
            <ul>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="bottom__footer">
      <div class="container__main d-flex justify-content-between">
        <button>Sign-up now</button>
        <div class="d-flex gap-2 align-items-center">
          <h3 class="mb-0 text-nowrap me-3">Follow us</h3>
          <img src="/img/footer-facebook.png" alt="social" />
          <img src="/img/footer-twitter.png" alt="social" />
          <img src="/img/footer-youtube.png" alt="social" />
          <img src="/img/footer-pinterest.png" alt="social" />
          <img src="/img/footer-periscope.png" alt="social" />
        </div>
      </div>
    </div>
  </footer>
</template>
<style lang="scss" scoped>
footer {
  background-color: #303030;
  min-height: 100px;
  color: white;

  ul {
    list-style: none;
    padding: 0;
    color: rgba(255, 255, 255, 0.5);
  }

  h3 {
    text-transform: uppercase;
    font-family: $menu-font;
    font-weight: 600;
  }

  .top__footer {
    padding: 2em 0;
    background-image: url("/img/dc-logo-bg.png"), url("/img/footer-bg.jpg");
    background-repeat: no-repeat, repeat;
    background-position: 90%, 0;
  }

  .bottom__footer {
    button {
      text-transform: uppercase;
      font-family: $menu-font;
      color: white;
      background-color: transparent;
      border: solid 3px $accent-color;
      padding: 5px 20px;
    }

    img {
      aspect-ratio: 1;
    }

    h3 {
      color: $accent-color;
    }
  }
}
</style>
