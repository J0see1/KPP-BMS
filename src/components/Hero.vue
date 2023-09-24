<script>
import { useRouter } from "vue-router";
</script>

<template>
  <section class="navbar">
    <div class="logo">
      <a href="#"> Portal </a>
    </div>
    <div class="menu">
      <ul>
        <li><a href="#">home</a></li>
        <li><a href="#">about</a></li>
        <li><a href="#">content</a></li>
      </ul>
    </div>
  </section>
  <section class="hero">
    <div class="tag">
      <p>Hi, we are group 7 feel free to have a tour!!</p>
      <button><a href="#"> content</a></button>
    </div>
  </section>
  <section class="about-us">
    <p>About Us</p>
    <div class="cards-collide">
      <div class="card">
        <img src="../assets/Rectangle 6.svg" alt="" width="200px" />
        <p>Marcelinus Alvinanda Chrisantya</p>
      </div>
      <div class="card">
        <img src="../assets/Rectangle 6.svg" alt="" width="200px" />
        <p>Marcelinus Alvinanda Chrisantya</p>
      </div>
      <div class="card">
        <img src="../assets/Rectangle 6.svg" alt="" width="200px" />
        <p>Marcelinus Alvinanda Chrisantya</p>
      </div>
      <div class="card">
        <img src="../assets/Rectangle 6.svg" alt="" width="200px" />
        <p>Marcelinus Alvinanda Chrisantya</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* hero */
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

/* hero */
.hero {
  width: 100%;
  background: linear-gradient(180deg, #136f63 0%, #84dcc6 100%);
}

.tag {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.tag > p {
  margin-top: 150px;
  color: #fff;
  text-align: center;
  font-family: Montserrat, sans-serif;
  font-size: 64px;
  font-style: normal;
  font-weight: 900;
  line-height: normal;
  width: 757px;
  text-transform: uppercase;
}

.tag > button {
  width: auto;
  border-radius: 50px;
  border: 3px solid #000;
  background: #fff;
  box-shadow: 5px 10px 4px 0px rgba(0, 0, 0, 0.25);
  padding: 15px 50px;
  margin: 50px 0px 190px 0px;
}

button > a {
  color: #222;
  text-align: center;
  font-family: Montserrat, sans-serif;
  font-size: 36px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  text-transform: uppercase;
}

/* about us */

.about-us {
  background: linear-gradient(180deg, #84dcc6 0%, #136f63 97.12%);
}

.about-us > p {
  color: #fdfffd;
  text-align: center;
  text-shadow: 5px 10px 4px rgba(0, 0, 0, 0.25);
  font-family: Montserrat, sans-serif;
  font-size: 56px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  padding: 80px;
}

.cards-collide {
  display: flex;
  justify-content: space-around;
  gap: 10px;
  padding-bottom: 100px;
}

.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #fff;
  gap: 20px;
  border-radius: 20px;
  padding: 10px;
}

.card > img {
  padding: 0px;
  padding-top: 20px;
}

.card > p {
  color: #000;
  text-align: center;
  font-family: Montserrat;
  font-size: 23.75px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  width: 250px;
  padding-bottom: 20px;
}
</style>
