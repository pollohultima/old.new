<template>
  <header id="site_header">
    <div class="container px-0">
      <nav class="navbar navbar-light d-md-block d-none navbar-expand-md py-0">
        <div class="container justify-content-end">
          <a class="navbar-brand" href="#">
            <img class="img-fluid" src="" alt="" />
          </a>
          <button
            class="navbar-toggler tog"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarTogglerDemo01"
            aria-controls="navbarTogglerDemo01"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <div class="navbar-toggler-icon"></div>
          </button>

          <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
            <ul class="navbar-nav mx-auto mb-2 mb-lg-0 text-end">
              <li class="nav-item">
                <router-link class="nav-link" to="/">HOME</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/roadmap"
                  >ROADMAP</router-link
                >
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/nftgallery"
                  >NFT GALLERY</router-link
                >
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/about">ABOUT ME</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/contacts"
                  >CONTACTS</router-link
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<script></script>

<style lang="scss">
header {
  position: sticky;
  top: 0px;
  z-index: 1;
  background-color: #7cc0fc;

  nav {
    height: 100px;

    .navbar-brand {
      height: 100px;
      padding: 0 !important;
      img {
        height: 100px;
      }
    }

    .container {
      border-bottom: 1px solid black;

      a {
        text-decoration: none;
        color: black;
        letter-spacing: 3px;
        font-size: 14px;
        padding: 10px 30px;
        margin: 0px 15px;
        font-weight: bolder;
        background-image: linear-gradient(
          rgba(yellow, 0.5) 0%,
          rgba(yellow, 0.5) 100%
        );
        background-repeat: repeat-y;
        background-size: 0% 0em;
        background-position: 0 65%;
        transition: 600ms ease;

        &:hover {
          color: black !important;
          font-weight: 900;
          background-image: linear-gradient(
            rgba(yellow, 1) 0%,
            rgba(yellow, 1) 100%
          );
          background-size: 100% 1em;
        }

        &.router-link-exact-active {
          color: black !important;
          font-weight: 900;
          background-image: linear-gradient(
            rgba(yellow, 1) 0%,
            rgba(yellow, 1) 100%
          );
          background-size: 100% 1em;
        }
      }
    }
  }
}
</style>
