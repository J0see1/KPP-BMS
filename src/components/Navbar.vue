<script></script>

<template>
  <section class="navbar">
    <div class="logo">
      <a href="/"> Portal </a>
    </div>
    <div class="menu">
      <ul>
        <li><a href="#">home</a></li>
        <li><a href="#about-us">about</a></li>
        <li><a href="#content">content</a></li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
* {
  text-decoration: none;
  margin: 0;
  padding: 0;
}

.navbar {
  display: flex;
  justify-content: space-between;
  background-color: #80dbc4;
}

.logo {
  padding: 18px;
}

.logo > a {
  color: #222;
  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  font-family: Poppins, sans-serif;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  padding: 20px;
}

ul {
  display: flex;
  justify-content: space-evenly;
  gap: 10px;
  /* padding: 10px; */
}

li {
  list-style: none;
  padding: 30px;
}

li > a {
  color: #222;
  font-family: Poppins, sans-serif;
  font-size: 24px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
}
</style>
