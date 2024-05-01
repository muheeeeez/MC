<template>
  <div class="container">
    <div class="picture-container">
      <img src="../img/Grouphome.jpg" alt="" />
    </div>
    <div class="info-container">
      <div class="information">
        <h1>How it works</h1>
        <p>
          Commission-free multi-friendly real estate investing. Helping our
          friends build passive monthly income.
        </p>
      </div>
      <div class="details-container">
        <div class="details">
          <div><img src="../img/Group 6home-icon.jpg" class="images" /></div>
          <div class="text">
            <h1>We buy</h1>
            <p>We find, negotiate, and purchase the deals.</p>
          </div>
        </div>
        <div class="details">
          <div>
            <img src="../img/Group 10dolllar-icon.jpg" class="images" />
          </div>
          <div class="text">
            <h1>You Invest</h1>
            <p>
              As an investor, you become a partner (called an “LP”) in the real
              estate.
            </p>
          </div>
        </div>
        <div class="details">
          <div><img src="../img/Group 13key-icon.jpg" class="images" /></div>
          <div class="text">
            <h1>We Manage</h1>
            <p>We manage the property and residents pay rent.</p>
          </div>
        </div>
        <div class="details">
          <div><img src="../img/Group 16smile-icons.jpg" class="images" /></div>
          <div class="text">
            <h1>You Get Paid</h1>
            <p>We send you, the investor, recurring cash distributions.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  margin: 80px 0px;
}
.picture-container {
  margin: auto;
}
.information {
  width: 392px;
  height: 110px;
}
.information h1 {
  width: 242px;
  height: 46px;
  font-family: "Ubuntu", sans-serif;
  font-size: 40px;
  font-weight: 500;
  line-height: 45.96px;
}
.information p {
  width: 410px;
  height: 50px;
  font-family: "Ubuntu", sans-serif;
  font-size: 17px;
  font-weight: 400;
  line-height: 19.53px;
}
.details-container {
  width: 392px;
}
.images {
  margin-top: 15px;
}
.details {
  display: flex;
  gap: 20px;
  margin-top: 40px;
}
.text {
  width: 346px;
  height: 52px;
}
.text h1 {
  width: 125px;
  height: 23px;
  font-family: "Ubuntu", sans-serif;
  font-weight: 800;
  font-size: 20px;
  line-height: 22.98px;
}
.text p {
  width: 346px;
  height: 21px;
  font-family: "Ubuntu", sans-serif;
  font-size: 18px;
  line-height: 20.68px;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  img {
    display: none;
  }
  .container {
    margin: 10px 0 60px 0;
  }
  .details-container,
  .text p,
  .information,
  .information p {
    width: 95vw;
  }
  .information h1 {
    font-weight: 1000;
  }
}
</style>