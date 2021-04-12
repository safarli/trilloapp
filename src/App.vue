<template>
  <div class="container">
    <header class="header">
      <!-- <img src="@/assets/logo.png" alt="trillo logo" class="logo"> -->
      <form action="#" class="search">
        <input
          type="text"
          name=""
          id=""
          class="search__input"
          placeholder="Search hotels"
        />
        <button class="search__button">
          <svg class="search__icon">
            <use
              xlink:href="@/assets/svg/sprite.svg#icon-magnifying-glass"
            ></use>
          </svg>
        </button>
      </form>

      <nav class="user-nav">
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use xlink:href="@/assets/svg/sprite.svg#icon-bookmark"></use>
          </svg>
          <span class="user-nav__notification">7</span>
        </div>
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use xlink:href="@/assets/svg/sprite.svg#icon-chat"></use>
          </svg>
          <span class="user-nav__notification">13</span>
        </div>
        <div class="user-nav__user">
          <img
            src="@/assets/img/me.jpeg"
            alt="me"
            class="user-nav__user-photo"
          />
          <span class="user-nav__user-name">Jonas</span>
        </div>
      </nav>
    </header>

    <div class="content">
      <nav class="sidebar"></nav>
      <main class="hotel-view">Hotel view</main>
    </div>
    <footer class="footer">Copyright. Wavevo 2021</footer>
  </div>
</template>


<script>
export default {
  data() {
    return {};
  },
  methods: {},
};
</script>


<style lang="scss">
@use '@/scss/main.scss';
</style>