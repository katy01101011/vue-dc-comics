<template>
  <header>
    <div class="container header">
      <div class="header__logo">
        <img src="../assets/dc-logo.png" alt="">
      </div>
      <ul class="header__menu">
        <li v-for="(item, index) in links" :key="index">
          <a href="">{{ item.text }}</a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
  data: function() {
    return {
      links: [
        {
          url: "#",
          text: Characters,
          active: false,
        },
                {
          url: "#",
          text: Comics,
          active: true,
        },
        {
          url: "#",
          text: Movies,
          active: false,
        },
        {
          url: "#",
          text: Tv,
          active: false,
        },
        {
          url: "#",
          text: Games,
          active: false,
        },
          {
          url: "#",
          text: Collectibles,
          active: false,
        },
        {
          url: "#",
          text: Videos,
          active: false,
        },
        {
          url: "#",
          text: Fans,
          active: false,
        },
        {
          url: "#",
          text: News,
          active: false,
        },
        {
          url: "#",
          text: Shop,
          active: false,
        }
      ]
    }
  }
};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;

  &__logo {
    img {
      height: 115px;
    }
  }

  &__menu {
    display: flex;

    li {
      margin-left: 2rem;
      
      a {
        color: $black-color;
        text-transform: uppercase;
        font-size: 1.3rem;
        line-height: 150px;
      }

      &.active {
        border-bottom: 10px solid $blue-color;
      }
    }
  }
}

</style>
