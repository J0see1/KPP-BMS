<script>
export default {
  AboutUs,
};
</script>

<template>
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

<style>
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
