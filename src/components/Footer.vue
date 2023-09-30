<template>
  <section class="navbar">
    <div class="logo">
      <p>Contact us:</p>
    </div>
    <div class="menu">
      <ul>
        <li>
          <a href="https://www.instagram.com/_fif.17/" target="_blank"
            >@fif_17</a
          >
        </li>
        <li>
          <a href="https://www.instagram.com/mreezx/" target="_blank"
            >@mreezx</a
          >
        </li>
        <li>
          <a href="https://www.instagram.com/viansyah._/" target="_blank"
            >@viansyah._</a
          >
        </li>
        <li>
          <a href="https://www.instagram.com/r.dhim/" target="_blank">
            @r.dhim</a
          >
        </li>
      </ul>
    </div>
    <div>
      <p></p>
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
  width: 100%;
  justify-content: baseline;
  background-color: #80dbc4;
}

.logo {
  display: block;
  padding: 10px 18px 10px;
}

.logo > p {
  color: #222;
  font-family: Montserrat, sans-serif;
  font-size: 40px;
  font-style: normal;
  font-weight: 200;
  line-height: normal;
  padding: 10px 10px;
}

.menu {
  display: flex;
  justify-self: center;
  justify-content: center;
  padding-bottom: 10px;
}

ul {
  display: inline-flex;
  justify-content: space-evenly;
  gap: 10px;
  /* padding: 10px; */
}

li {
  list-style: none;
  padding: 30px 50px 10px;
}

li > a {
  color: #222;
  font-family: Poppins, sans-serif;
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
</style>
