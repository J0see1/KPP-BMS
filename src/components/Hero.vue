<script></script>

<template>
  <!-- <section class="navbar">
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
  </section> -->
  <section class="hero">
    <div class="tag">
      <p>Hi, we are group 7 feel free to have a tour!!</p>
      <button><a href="#content"> content</a></button>
    </div>
  </section>
  <!-- <section class="about-us">
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
  </section> -->
</template>

<style scoped>
* {
  text-decoration: none;
  margin: 0;
  padding: 0;
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
  color: #fff;
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

.tag button:hover {
  background: #6f8ab7;
}
</style>
/* about us */
