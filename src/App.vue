<script setup>
import MeInfo from "./components/MeInfo.vue";
import HomeList from "./components/HomeList.vue";
</script>

<template>
  <header>
    <img
      alt="Logo"
      class="logo"
      src="./assets/logo.svg"
      width="125"
      height="125"
    />

    <div class="wrapper">
      <MeInfo />
    </div>
  </header>

  <main>
    <HomeList />
  </main>
</template>

<style>
@import "./assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}

header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

ul {
  list-style-type: square;
  margin: 2px;
  margin-left: 1.5rem;
  padding: 0;
}

a,
.green {
  text-decoration: none;
  color: rgb(223, 120, 24);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(36, 82%, 26%, 0.2);
  }
}

@media (min-width: 1024px) {
  body {
    display: flex;
    place-items: center;
  }

  #app {
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding: 0 2rem;
  }

  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  .logo {
    margin: 0 2rem 0 0;
  }
}
</style>