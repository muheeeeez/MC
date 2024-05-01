<template>
  <div class="container">
    <div class="text">
      <h4>Put your money in motion through real estate</h4>
      <p>
        We are a private equity company helping our friends build passive income
        through commercial real estate. We buy distressed, unsexy assets that
        produce high cash returns.
      </p>
      <button>Invest Now</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  height: 659px;
  background-color: #c3f53d;
  /* border-radius: 28.5px; */
  padding-top: 132px;
  box-sizing: border-box;
}
.text {
  width: 655px;
  height: 344px;
  z-index: 100;
  margin-left: 386px;
  color: #000000;
}
.text h4 {
  width: 653px;
  height: 116px;
  font-family: "Ubuntu", sans-serif;
  font-weight: 900;
  font-size: 52px;
  line-height: 59.75px;
}
.text p {
  width: 603px;
  height: 130px;
  font-family: "Ubuntu", sans-serif;
  font-weight: 600;
  font-size: 22px;
  line-height: 35px;
}
.text button {
  width: 154px;
  height: 52px;
  border-radius: 28.5px;
  font-family: "Ubuntu", sans-serif;
  font-size: 16px;
  font-weight: 500;
  line-height: 18.38px;
  color: #fff;
  background-color: #000;
  cursor: pointer;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  .container {
    width: 100vw;
    height: 110vh;
    padding: 0;
  }
  .text h4,
  .text p {
    padding-top: 30px;
    width: 100vw;
    height: 35vh;
  }

  .text p {
    width: 100vw;
  }
  .text {
    width: 100vw;
    margin-left: 4px;
  }
}
</style>