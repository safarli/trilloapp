<template>
  <div class="container">
    <!-- HEADER START -->
    <header class="header">
      <img src="@/assets/logo.png" alt="trillo logo" class="logo" />
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
            <use href="/svg/sprite.svg#icon-magnifying-glass"></use>
          </svg>
        </button>
      </form>

      <!-- USER NAV START -->
      <nav class="user-nav">
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use href="/svg/sprite.svg#icon-bookmark"></use>
          </svg>
          <span class="user-nav__notification">7</span>
        </div>
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use href="/svg/sprite.svg#icon-chat"></use>
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
      <!-- USER NAV END -->
    </header>
    <!-- HEADER END -->

    <div class="content">
      <!-- SIDEBAR START -->
      <nav class="sidebar">
        <!-- SIDE NAV-BAR START -->
        <ul class="side-nav">
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use href="/svg/sprite.svg#icon-home"></use>
              </svg>
              <span>Home</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use href="/svg/sprite.svg#icon-aircraft-landing"></use>
              </svg>
              <span>Home</span>
            </a>
          </li>
          <li class="side-nav__item side-nav__item--active">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use href="/svg/sprite.svg#icon-key"></use>
              </svg>
              <span>Home</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use href="/svg/sprite.svg#icon-map"></use>
              </svg>
              <span>Home</span>
            </a>
          </li>
        </ul>
        <!-- SIDE NAV-BAR END -->
        <div class="legal">&copy; 2021 by Wavevo. All rights reserved.</div>
      </nav>
      <!-- SIDEBAR END -->

      <main class="hotel-view">
        <!-- GALLERY -->
        <div class="gallery">
          <figure class="gallery__item">
            <img
              src="/img/hotel-1.jpg"
              alt="Photo of hotel 1"
              class="gallery__photo"
            />
          </figure>
          <figure class="gallery__item">
            <img
              src="/img/hotel-2.jpg"
              alt="Photo of hotel 2"
              class="gallery__photo"
            />
          </figure>
          <figure class="gallery__item">
            <img
              src="/img/hotel-3.jpg"
              alt="Photo of hotel 3"
              class="gallery__photo"
            />
          </figure>
        </div>
        <!-- GALLERY END -->

        <!-- OVERVIEW START-->
        <div class="overview">
          <h1 class="overview-heading">Hotel Las Palmas</h1>
          <div class="overview__stars">
            <svg class="overview__icon-star">
              <use href="/svg/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use href="/svg/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use href="/svg/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use href="/svg/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use href="/svg/sprite.svg#icon-star"></use>
            </svg>
          </div>

          <div class="overview__location">
            <svg class="overview__icon-location">
              <use href="/svg/sprite.svg#icon-location-pin"></use>
            </svg>
            <button class="btn-inline">Albufeira, Portugal</button>
          </div>

          <div class="overview__rating">
            <div class="overview__rating-average">8.2</div>
            <div class="overview__rating-count">429 votes</div>
          </div>
        </div>
        <!-- OVERVIEW END -->

        <!-- DETAIL START -->
        <div class="detail">
          <!-- DESCRIPTION START -->
          <div class="description">
            <p class="paragraph">
              LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISICING ELIT. SINT
              fugiat est itaque. Minima, perferendis reprehenderit. Sequi quo
              nostrum eveniet. Porro maxime assumenda vero officia eius id odit
              illo aut tempore.
            </p>
            <p class="paragraph">
              Assumenda tenetur harum recusandae voluptatibus voluptas nostrum
              officiis porro, itaque dicta ea incidunt excepturi veritatis
              suscipit similique temporibus quisquam minus rerum dolor.
            </p>
            <ul class="list">
              <li class="list__item">Close to the beach</li>
              <li class="list__item">Breakfast included</li>
              <li class="list__item">Free airport shuttle</li>
              <li class="list__item">Free wifi on all rooms</li>
              <li class="list__item">Air conditioning and heating</li>
              <li class="list__item">Pets allowed</li>
              <li class="list__item">We speak all languages</li>
              <li class="list__item">Perfect for families</li>
            </ul>

            <div class="recommend">
              <p class="recommend__count">
                Lucy and 3 other friends recommend this hotel.
              </p>
              <div class="recommend__friends">
                <img
                  src="/img/persons/man-1.jpg"
                  alt="Friend 1"
                  class="recommend__photo"
                />
                <img
                  src="/img/persons/woman-1.jpg"
                  alt="Friend 2"
                  class="recommend__photo"
                />
                <img
                  src="/img/persons/man-2.jpg"
                  alt="Friend 3"
                  class="recommend__photo"
                />
                <img
                  src="/img/persons/man-3.jpg"
                  alt="Friend 4"
                  class="recommend__photo"
                />
              </div>
            </div>
          </div>
          <!-- DESCRIPTION END -->

          <!-- USER REVIEWS START -->
          <div class="user-reviews">
            <!-- REVIEW START-->
            <figure class="review">
              <blockquote class="review__text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus
                quis voluptatum voluptatem, omnis consectetur harum iste dolore
                deleniti minima, reiciendis veritatis vero alias sit blanditiis
                eaque fugiat eveniet unde necessitatibus!
              </blockquote>
              <figcaption class="review__user">
                <img
                  src="/img/persons/man-3.jpg"
                  alt=""
                  class="review__user-photo"
                />
                <div class="review__user-box">
                  <p class="review__user-name">Nick Smith</p>
                  <p class="review__user-date">April 14th, 2021</p>
                </div>
                <div class="review__rating">7.8</div>
              </figcaption>
            </figure>
            <!-- REVIEW END -->

            <!-- REVIEW START -->
            <figure class="review">
              <blockquote class="review__text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus
                quis voluptatum voluptatem, omnis consectetur harum iste dolore
                deleniti minima, reiciendis veritatis vero alias sit blanditiis
                eaque fugiat eveniet unde necessitatibus!
              </blockquote>
              <figcaption class="review__user">
                <img
                  src="/img/persons/woman-2.jpg"
                  alt=""
                  class="review__user-photo"
                />
                <div class="review__user-box">
                  <p class="review__user-name">Jessica Sun</p>
                  <p class="review__user-date">December 26th, 2021</p>
                </div>
                <div class="review__rating">8.1</div>
              </figcaption>
            </figure>
            <!-- REVIEW END -->

            <!-- set tabindex to 1 for getting focus on div element (or use button), default is 0 -->
            <div class="btn-inline" tabindex="1">
              Show all <span>&rarr;</span>
            </div>
          </div>
          <!-- USER REVIEWS END -->
        </div>
        <!-- DETAIL END -->
      </main>
    </div>
  </div>
</template>


<script>
// import Icon from '@/components/Icon.vue';

export default {
  data() {
    return {};
  },
  methods: {},
  components: {
    // Icon,
  },
};
</script>


<style lang="scss">
@use '@/scss/main.scss';
</style>