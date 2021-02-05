<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "assets/sass/style.scss";
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap");

:root {
  --primary: #eb2f64;
  --primary-light: #ff3366;
  --primary-dark: #ba265d;

  --gray-light-1: #faf9f9;
  --gray-light-2: #f4f2f2;
  --gray-light-3: #f0eeee;
  --gray-light-4: #ccc;

  --gray-dark-1: #333;
  --gray-dark-2: #777;
  --gray-dark-3: #999;

  --shadow-dark: 0 2rem 6rem rgba(0,0,0,.3);
}

* {
  margin: 0;
  padding: 0;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  box-sizing: border-box;
  font-size: 62.5%; // 1rem = 10px, 10px/16px = 62.5%
}

body {
  font-family: "Open Sans", sans-serif;
  font-weight: 400;
  line-height: 1.6rem;
  color: var(--gray-dark-2);
  background-image: linear-gradient(to right bottom, var(--primary-light), var(--primary-dark));
  background-size: cover;
  background-repeat: no-repeat;
  min-height: 100vh;
}
</style>
