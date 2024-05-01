<template>
  <div class="container">
    <div>
      <h1 class="title">Our Portfolio</h1>
    </div>
    <div class="card-container">
      <div class="card">
        <div class="card-content">
          <img
            src="../img/card-image.jpg"
            alt="card-image"
            class="card-image"
          />
          <div class="card-text">
            <h1>Tacoma Waterfront Condos</h1>
            <p>1236 S Alaska St., Tacoma, WA 98004</p>
          </div>
          <hr />
          <div class="card-details">
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/house-value 1.jpg" alt="" />
                </div>
                <div>
                  <p>Value</p>
                  <h1>$ 3,196,000</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/database 1.jpg" alt="" />
                </div>
                <div class="text-color">
                  <p>Units</p>
                  <h1>6</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/chart-pie 1.jpg" alt="" />
                </div>
                <div>
                  <p>CAP</p>
                  <h1>6%</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/trim 1.jpg" alt="" />
                </div>
                <div class="text-color">
                  <p>NRSF</p>
                  <h1>12,607</h1>
                </div>
              </div>
            </div>
          </div>
          <div class="card-button">
            <button class="mybtn">Learn more</button>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-content">
          <img
            src="../img/card-image.jpg"
            alt="card-image"
            class="card-image"
          />
          <div class="card-text">
            <h1>Tacoma Waterfront Condos</h1>
            <p>1236 S Alaska St., Tacoma, WA 98004</p>
          </div>
          <hr />
          <div class="card-details">
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/house-value 1.jpg" alt="" />
                </div>
                <div>
                  <p>Value</p>
                  <h1>$ 3,196,000</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/database 1.jpg" alt="" />
                </div>
                <div class="text-color">
                  <p>Units</p>
                  <h1>6</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/chart-pie 1.jpg" alt="" />
                </div>
                <div>
                  <p>CAP</p>
                  <h1>6%</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/trim 1.jpg" alt="" />
                </div>
                <div class="text-color">
                  <p>NRSF</p>
                  <h1>12,607</h1>
                </div>
              </div>
            </div>
          </div>
          <div class="card-button">
            <button class="mybtn">Learn more</button>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-content">
          <img
            src="../img/card-image.jpg"
            alt="card-image"
            class="card-image"
          />
          <div class="card-text">
            <h1>Tacoma Waterfront Condos</h1>
            <p>1236 S Alaska St., Tacoma, WA 98004</p>
          </div>
          <hr />
          <div class="card-details">
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/house-value 1.jpg" alt="" />
                </div>
                <div>
                  <p>Value</p>
                  <h1>$ 3,196,000</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/database 1.jpg" alt="" />
                </div>
                <div class="text-color">
                  <p>Units</p>
                  <h1>6</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/chart-pie 1.jpg" alt="" />
                </div>
                <div>
                  <p>CAP</p>
                  <h1>6%</h1>
                </div>
              </div>
            </div>
            <div>
              <div class="card-info">
                <div class="rounded-container">
                  <img src="../img/trim 1.jpg" alt="" />
                </div>
                <div class="text-color">
                  <p>NRSF</p>
                  <h1>12,607</h1>
                </div>
              </div>
            </div>
          </div>
          <div class="card-button">
            <button class="mybtn">Learn more</button>
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
  margin: 0 auto;
  padding: 0;
  height: 892px;
  background: black;
}
.title {
  /* width: 248px; */
  height: 46px;
  text-align: center;
  padding: 50px;
  font-family: "Ubuntu", sans-serif;
  font-size: 45px;
  font-weight: 500;
  line-height: 45.96px;
  color: #fff;
}
.card-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 70px;
}
.card {
  width: 368px;
  height: 536px;
  background: #161616;
  border-radius: 12px;
  border: 1px solid #161616;
  overflow: hidden;
  /* box-shadow: ; */
}
.card-image {
  border-radius: 12px;
  border: 1px;
}
.card-content {
  padding: 20px;
}
.card-text h1 {
  width: 254px;
  height: 23px;
  font-family: "Ubuntu", sans-serif;
  font-size: 20px;
  font-weight: 500;
  line-height: 22.98px;
  color: #ffff;
}
.card-text p {
  width: 233.18px;
  height: 16px;
  font-family: "Ubuntu", sans-serif;
  font-size: 14px;
  font-weight: 300;
  line-height: 16.09px;
  color: rgba(255, 255, 255, 1);
}
.card-details {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.card-info {
  display: flex;
  gap: 20px;
  align-items: center;
  color: #fff;
}
.card-info p {
  width: 24px;
  height: 10px;
  font-family: "Ubuntu", sans-serif;
  font-size: 9px;
  font-weight: 500;
  line-height: 10.34px;
}
.card-info h1 {
  width: 92px;
  height: 21px;
  font-family: "Ubuntu", sans-serif;
  font-size: 17.5px;
  font-weight: 500;
  line-height: 20.68px;
}
.rounded-container {
  width: 38px;
  height: 38px;
  text-align: center;
  background-color: #fff;
  border-radius: 50%;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
}
.text-color {
  color: rgba(255, 209, 209, 1);
}
.card-button {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 30px;
}
.mybtn {
  width: 223px;
  height: 41px;
  border-radius: 20.5px;
  background: #c3f53d;
  border: 1px solid #c3f53d;
  cursor: pointer;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  .container {
    height: 100vh;
  }
  .card-container {
    gap: 20px;
  }
  .card-info {
    gap: 0;
  }
}
</style>