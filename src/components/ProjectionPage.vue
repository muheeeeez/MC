<template>
  <div class="container">
    <div class="right-container">
      <div>
        <h1>$ 1000</h1>
        <p>Donated to charity</p>
      </div>
      <div>
        <h1>$ 10m</h1>
        <p>Property Portfoliio Value</p>
      </div>
      <div>
        <h1>100%</h1>
        <p>Occupancy</p>
      </div>
      <div>
        <h1>$500,000</h1>
        <p>2020 Revenues</p>
      </div>
      <div>
        <h1>30%</h1>
        <p>Net LTV</p>
      </div>
      <div class="image-container">
        <img src="../img/Framehalfhome1.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  height: 519px;
  background-color: #f0ebe6;
  margin-bottom: -29px;
}
.right-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 0.5fr;
  gap: 20px;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.right-container h1 {
  font-family: "Ubuntu", sans-serif;
  font-weight: 700;
  font-size: 35px;
  line-height: 40.22px;
}
.right-container p {
  font-family: "Ubuntu", sans-serif;
  font-size: 17px;
  font-weight: 400;
  line-height: 19.53px;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  img {
    display: none;
  }
  .right-container {
    display: flex;
    flex-wrap: wrap;
  }
  .container {
    width: 100vw;
   
  }
}
</style>