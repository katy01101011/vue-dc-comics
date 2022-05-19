<template>
  <main>
      <div class="container">
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
          <div class="card">
              <div class="card__img">
                  <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
              </div>
              <div class="card__text">
                  <span>Title</span>
              </div>
          </div>
      </div>
  </main>
</template>

<script>
export default {
    name: "AppMain",
}
</script>

<style lang="scss" scoped>
    @import "../style/variables.scss";
    main {
        width: 100%;
        background-color: $black-color;

        .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        padding-top: 2rem;
        padding-bottom: 2rem;

            .card {
            width: 250px;
            margin: 2rem 1rem;

            &__img {
                width: 100%;
                height: 250px;
                overflow: hidden;

                img {
                    width: 100%;
                }

            }

            &__text {
                color: white;
                text-transform: uppercase;
                padding-top: 1rem;

            }
        }
        }
    }
</style>