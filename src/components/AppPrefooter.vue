<template>
  <div class="prefooter-container">
    <div class="container prefooter">
      <div class="prefooter__col">
        <ul>
          <h3>DC Comics</h3>
          <li v-for="(element, index) in comicsLinks" :key="index">
            <a href="">{{ element.text }}</a>
          </li>
        </ul>
        <ul>
          <h3>DC Shop</h3>
          <li v-for="(element, index) in shopLinks" :key="index">
            <a href="">{{ element.text }}</a>
          </li>
        </ul>
      </div>
      <div class="prefooter__col">
        <ul>
          <h3>DC</h3>
          <li v-for="(element, index) in dcLinks" :key="index">
            <a href="">{{ element.text }}</a>
          </li>
        </ul>
      </div>
      <div class="prefooter__col">
        <ul>
          <h3>Sites</h3>
          <li v-for="(element, index) in sitesLinks" :key="index">
            <a href="">{{ element.text }}</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppPrefooter",
  data: function () {
    return {
      comicsLinks: [
        {
          text: "Characters",
          url: "#",
        },
        {
          text: "Comics",
          url: "#",
        },
        {
          text: "Movies",
          url: "#",
        },
        {
          text: "TV",
          url: "#",
        },
        {
          text: "Games",
          url: "#",
        },
        {
          text: "Videos",
          url: "#",
        },
        {
          text: "News",
          url: "#",
        },
      ],
      shopLinks: [
        {
          text: "Shop DC",
          url: "#",
        },
        {
          text: "Shop DC Collectibles",
          url: "#",
        },
      ],
      dcLinks: [
        {
          text: "Terms Of Use",
          url: "#",
        },
        {
          text: "Privacy Policy (New)",
          url: "#",
        },
        {
          text: "Ad Choices",
          url: "#",
        },
        {
          text: "Advertising",
          url: "#",
        },
        {
          text: "Jobs",
          url: "#",
        },
        {
          text: "Subscriptions",
          url: "#",
        },
        {
          text: "CPSC Certificates",
          url: "#",
        },
        {
          text: "Ratings",
          url: "#",
        },
        {
          text: "Shop Help",
          url: "#",
        },
        {
          text: "Contact Us",
          url: "#",
        },
      ],
      sitesLinks: [
        {
          text: "DC",
          url: "#",
        },
        {
          text: "DC UNIVERSE INFINITE",
          url: "#",
        },
        {
          text: "DC Kids",
          url: "#",
        },
        {
          text: "DC Shop",
          url: "#",
        },
        {
          text: "MAD Magazine",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.prefooter-container {
  width: 100%;
  background-image: url(../assets/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;

  .prefooter {
    display: flex;
    padding-top: 3rem;
    padding-bottom: 4rem;
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: 830px;
    background-position-y: 50%;
    background-position-x: 100%;

    &__col {
      width: 300px;
    }

    a {
      color: darkgray;
      line-height: 2rem;
      font-size: 1.2rem;
      font-weight: 300;
    }

    h3 {
      line-height: 5rem;
      text-transform: uppercase;
      font-size: 2rem;
      font-weight: 500;
      color: white;
    }
  }
}
</style>
