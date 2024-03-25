<template>
  <main>
    <div class="main-header">
      <div class="button-main-catalog">
        <a href="#">Woman's Fashion <b>></b> </a>
        <a href="#">Men's Fashion <b>></b> </a>
        <a href="#">Electronics</a>
        <a href="#">Home & Lifestyle</a>
        <a href="#">Medicine</a>
        <a href="#">Sports & Outdoor</a>
        <a href="#">Baby's & Toys</a>
        <a href="#">Groceries & Pets</a>
        <a href="#">Health & Beauty</a>
      </div>

      <div class="main-header-advertisment">
        <div class="apple-text">
          <div class="apple">
            <img src="../assets/img/1200px-Apple_gray_logo 1.png" alt="" />
            <h3>
              <span style="color: white; margin-left: 10px"
                >iPhone 14 Series</span
              >
            </h3>
          </div>
          <div class="advertisment-text">
            <div class="text">
              <h1>
                Up to 10% <br />
                off Voucher
              </h1>
            </div>
            <div class="text-button">
              <a href="#">Shop Now</a>
              <img src="../assets/img/icons arrow-right.png" alt="" />
            </div>
          </div>
        </div>

        <div class="iphone">
          <img
            src="../assets/img/hero_endframe__cvklg0xk3w6e_large 2.png"
            alt=""
          />
        </div>

        <div class="dot">
          <img src="" alt="" />
        </div>
      </div>
    </div>

    <div class="day-sell">
      <div class="daynew">
        <div class="box">&nbsp;</div>
        <div>
          <h3>Today's</h3>
        </div>
      </div>
      <div class="timer">
        <div class="timer_text">
          <h1>Flash Sales</h1>
        </div>
        <div class="clock">
          <img src="../assets/img/Group 1000005937.png" alt="" />
        </div>
      </div>
      <div class="pip">
        <div class="seller">
          <div class="products">
            <div class="product">
              <div class="product_img">
                <img src="../assets/img/Frame 570.png" alt="" />
              </div>
            </div>
            <div class="product_text">
              <h3>HAVIT HV-G92 Gamepad</h3>
              <p>120$ <span>160$</span></p>
              <div class="rating-holder">
                <div class="c-rating c-rating--regular" data-rating-value="5">
                  <button>1</button>
                  <button>2</button>
                  <button>3</button>
                  <button>4</button>
                  <button>5</button>
                </div>
              </div>
            </div>
          </div>
          <div class="products">
            <div class="product">
              <div class="product_img">
                <img src="../assets/img/Frame 570 (2).png" alt="" />
              </div>
            </div>
            <div class="product_text">
              <h3>AK-900 Wired Keyboard</h3>
              <p
                style="
                  display: flex;
                  background-color: black;
                  align-items: center;
                  justify-content: space-evenly;
                  color: white;
                  width: 270px;
                  height: 41px;
                  border-radius: 0px, 0px, 4px, 4px;
                "
              >
                Add to cart
              </p>
              <p>960$ <span>1160$</span></p>
              <div class="rating-holder">
                <div class="c-rating c-rating--regular" data-rating-value="4">
                  <button>1</button>
                  <button>2</button>
                  <button>3</button>
                  <button>4</button>
                  <button>5</button>
                </div>
              </div>
            </div>
          </div>
          <div class="products">
            <div class="product">
              <div class="product_img">
                <img src="../assets/img/Frame 570 (3).png" alt="" />
              </div>
            </div>
            <div class="product_text">
              <h3>IPS LCD Gaming Monitor</h3>
              <p>370$ <span>400$</span></p>
              <div class="rating-holder">
                <div class="c-rating c-rating--regular" data-rating-value="5">
                  <button>1</button>
                  <button>2</button>
                  <button>3</button>
                  <button>4</button>
                  <button>5</button>
                </div>
              </div>
            </div>
          </div>
          <div class="products">
            <div class="product">
              <div class="product_img">
                <img src="../assets/img/Frame 570 (4).png" alt="" />
              </div>
            </div>
            <div class="product_text">
              <h3>S-Series Comfort Chair</h3>
              <p>375$ <span>400$</span></p>
              <div class="rating-holder">
                <div class="c-rating c-rating--regular" data-rating-value="4.5">
                  <button>1</button>
                  <button>2</button>
                  <button>3</button>
                  <button>4</button>
                  <button>5</button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="qwerty">
          <div class="catalog">
            <h2>View All Products</h2>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.day-sell {
  margin-left: 135px;
  margin-top: 140px;
}

.qwerty {
  display: flex;
  justify-content: center;
  margin-top: 25px;
}

.catalog {
  display: flex;
  justify-content: center;
  background-color: rgba(219, 68, 68, 1);
  color: white;
  width: 234px;
  height: 56px;
  align-items: center;
}

.pip {
  height: 600px;
  border-bottom: 2px solid #ccc;
}

.seller {
  display: flex;
  gap: 30px;
}

.button-main-catalog {
  display: flex;
  flex-direction: column;
  margin-left: 134px;
}

.button-main-catalog a {
  text-decoration: none;
  color: black;
  padding: 10px;
}

.main-header {
  display: flex;
  margin-top: 50px;
}

.main-header-advertisment {
  background-color: black;
  display: flex;
  margin-left: 15%;
}

.apple-text {
  display: flex;
  flex-direction: column;
  margin-left: 30px;
  align-items: center;
  justify-content: space-evenly;
}

.apple {
  display: flex;
  align-items: flex-start;
}

.advertisment-text {
  flex-direction: column;
  display: flex;
  color: white;
}

.text-button {
  display: flex;
  align-items: center;
}

.text-button img {
  margin-left: 5px;
}

.text-button a {
  color: white;
}

.iphone {
  display: flex;
  align-items: center;
  margin-left: 15px;
}

.iphone img {
  width: 450px;
}

.dot {
  display: flex;
  align-items: center;
}

.daynew {
  display: flex;
  align-items: center;
  gap: 10px;
}

.daynew h3 {
  color: rgba(219, 68, 68, 1);
}

.box {
  border-radius: 5px;
  width: 20px;
  height: 40px;
  background-color: rgba(219, 68, 68, 1);
}

.timer {
  display: flex;
  gap: 30px;
}

.product_text span {
  color: gray;
  text-decoration: line-through;
}
</style>

<style scoped lang="scss">
@import url("https://fonts.googleapis.com/css?family=Roboto+Slab:400");

$rating-min-value: 0 !default;

$rating-max-value: 5 !default;

$rating-steps-value: 0.25 !default;

$rating-color-empty: "%23ddd" !default;

$rating-color-full: gold !default;

$rating-color-hover: grey !default;

$rating-icons-paths: (
  quarter: "M196.208 415.2v-224.8l-139.504 20.272 100.944 98.384-23.84 138.928z",
  half:
    "M258.672 64l-62.384 126.4-139.504 20.272 100.944 98.384-23.84 138.928 124.768-65.6v-318.4z",
  three-quarters:
    "M321.616 190.496l-0.656-0.096-62.384-126.4-62.384 126.4-139.504 20.272 100.944 98.384-23.84 138.928 124.768-65.6 63.024 33.136z",
  full:
    "M457.888 210.672l-139.504-20.272-62.384-126.4-62.384 126.4-139.504 20.272 100.944 98.384-23.84 138.928 124.768-65.6 124.768 65.6-23.84-138.928c0 0 100.944-98.384 100.944-98.384z",
);

@function rating-values() {
  $rating-values: ();

  @for $i
    from $rating-min-value
    through ($rating-max-value / $rating-steps-value)
  {
    $rating-value: abs($i * $rating-steps-value);
    $rating-values: append($rating-values, $rating-value, "comma");
  }

  @return $rating-values;
}

@function get-icon($icon, $color) {
  @if not index(quarter half three-quarters full, $icon) {
    @error "Interaction type must be either `quarter`, `half`, `three-quarters` or `full`.";
  }

  @return url("data:image/svg+xml;utf8,%3Csvg%20version%3D%221.1%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20width%3D%22512%22%20height%3D%22512%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22" + $color + "%22%20d%3D%22" + map-get(
        $rating-icons-paths,
        $icon
      ) + "%22%3E%3C%2Fpath%3E%3C%2Fsvg%3E")
    center / cover no-repeat;
}

@mixin c-rating(
  $star-size: 20px,
  $star-element: button,
  $interaction-type: representative
) {
  @if not index(clickable representative, $interaction-type) {
    @error "Interaction type must be either `clickable` or `representative`.";
  }

  #{$star-element} {
    display: inline-block;
    float: left;
    width: $star-size;
    height: $star-size;
    border: 0;
    text-indent: -9999px;
    outline: none;
    background: get-icon(full, $rating-color-empty);

    @if $interaction-type == clickable {
      cursor: pointer;
      transition: background 0.25s ease;

      // Override background images on hover state
      &:hover,
      &:hover ~ #{$star-element} {
        background: get-icon(full, $rating-color-empty) !important;
      }
    }
  }

  // Override background images on hover state
  @if $interaction-type == clickable {
    &:hover {
      #{$star-element} {
        background: get-icon(full, $rating-color-hover) !important;
      }
    }
  }

  @each $rating-value in rating-values() {
    // Get the next higher integer.
    $rating-value-ceil: ceil($rating-value);

    &[data-rating-value="#{$rating-value}"] {
      #{$star-element}:nth-child(-n + #{$rating-value-ceil}) {
        background: get-icon(full, $rating-color-full);
      }

      #{$star-element}:nth-child(#{$rating-value-ceil}) {
        // Evaluate which fraction of a star this value is and add the proper background
        @if str-slice("#{$rating-value}", 2, 4) == ".25" {
          background: get-icon(quarter, $rating-color-full),
            get-icon(full, $rating-color-empty);
        } @else if str-slice("#{$rating-value}", 2, 4) == ".5" {
          background: get-icon(half, $rating-color-full),
            get-icon(full, $rating-color-empty);
        } @else if str-slice("#{$rating-value}", 2, 4) == ".75" {
          background: get-icon(three-quarters, $rating-color-full),
            get-icon(full, $rating-color-empty);
        }
      }
    }
  }
}

@function toem($target, $context: 16px) {
  @if $target == 0 {
    @return 0;
  }

  @return $target / $context + 0em;
}

.wrapper {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 700px;
  transform: translate(-50%, -50%);

  h1 {
    margin-bottom: 75px;
    font-size: 56px;
    font-weight: 400;
    color: #fff;
  }
}

.rating-holder {
  display: inline-block;
  padding: toem(10px) toem(30px);
  margin: 0 10px;
  background-color: #fff;
  border-radius: toem(25px);
  box-sizing: border-box;
}

.c-rating {
  @include c-rating(toem(20px), button);

  &--small {
    font-size: 50%;
  }

  &--big {
    font-size: 150%;
  }
}
</style>
