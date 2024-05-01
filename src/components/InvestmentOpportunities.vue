<template>
  <div class="container">
    <div class="image-container">
      <img src="../img/graph.jpg" alt="" />
    </div>
    <div class="info">
      <h1>Investment Opportunities Coming Soon...</h1>
      <p>
        Commission-free multi-family real estate investing. Helping our friends
        build passive monthly income.
      </p>
      <button>Learn more</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  height: 649px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  background: #f0ebe6;
}
.info h1 {
  width: 502px;
  height: 111px;
  font-family: "Ubuntu", sans-serif;
  font-weight: 500;
  font-size: 40px;
  line-height: 45.96px;
}
.info p {
  width: 502px;
  height: 64px;
  font-family: "Ubuntu", sans-serif;
  font-weight: 400;
  font-size: 18px;
  line-height: 30px;
}
.info button {
  width: 137px;
  height: 47px;
  border-radius: 28.5px;
  background: #000;
  color: #fff;
  cursor: pointer;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  .container {
    width: 100vw;
    margin-top:1550px ;
  }
  img {
    width: 20px;
  }
  .info h1,
  .info p {
    width: 100vw;
  }
}
</style>