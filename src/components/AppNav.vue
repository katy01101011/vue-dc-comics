<template>
  <div class="total">
    <div class="container">
      <nav>
        <ul>
          <li>
            link
          </li>
          <li>
            link
          </li>
          <li>
            link
          </li>
          <li>
            link
          </li>
          <li>
            link
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
    name: "AppNav"
}
</script>

<style lang="scss" scoped>
  @import "../style/variables.scss";

  .total {
    background-color: $blue-color;
    height: 200px;

    nav {
      height: 200px;

    ul {
      height: 100%;
      display: flex;
      justify-content: space-around;
      align-items: center;
    }
  }
}
</style>