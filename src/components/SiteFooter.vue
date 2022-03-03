<template>
  <footer id="site_footer" class="mb-5">
    <div class="container-md container-fluid">
      <div class="foot_wrap d-flex align-items-center justify-content-center">
        <div class="follow ps-3">
          <h4 class="mb-0">Follow me:</h4>
        </div>
        <div class="icon_wrapper px-3">
          <a target="_blank" href="" class="px-2 fb"
            ><i class="fab fa-facebook-square"></i
          ></a>
          <a target="_blank" href="" class="px-2 ig"
            ><i class="fab fa-instagram"></i
          ></a>
          <!--  <a href="" class="px-2"><i class="far fa-envelope"></i></a> -->
        </div>
      </div>
    </div>
  </footer>

  <!-- Option 2: Separate Popper and Bootstrap JS -->
</template>

<style lang="scss">
footer {
  .container-md {
    padding: 20px 0;
    border-top: 1px solid black;

    .foot_wrap {
      .icon_wrapper {
        font-size: 30px;
        a {
          text-decoration: none;
          color: gray;
        }
        .fb {
          &:hover {
            color: #3b5998;
          }
        }

        .ig {
          &:hover {
            color: #c837ac;
          }
        }
      }
    }
  }
}
</style>
