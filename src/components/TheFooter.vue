<template>
  <div class="footer">
    <div class="container">
      <div class="header">
        <h1>MC</h1>
        <p>
          Commission-free multi-family real estate. Investing.Helping our
          friends build passive monthly income.
        </p>
      </div>
      <div class="info">
        <h1>Navigation links</h1>
        <ul>
          <li><a href="#">Investment</a></li>
          <li><a href="#">How it works</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Key figures</a></li>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">Newsletter</a></li>
        </ul>
      </div>
      <div class="subscribe">
        <h1>Newsletter</h1>
        <p>
          The 3-minute newsletter with fresh tweets on real estate news you need
          to start your week.
        </p>
        <label>
          <input type="text" placeholder="name@email.com" />
          <button>Subscribe</button>
        </label>
      </div>
    </div>
    <hr />
    <div class="copyright">
      <p>@2023 Robinhood. All rights reserved.</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  height: 573px;
  background-color: #000;
  color: #fff;
  font-family: "Ubuntu", sans-serif;
}
hr {
  width: 1875px;
  border: 1px solid #fff;
  margin-top: 50px;
}

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  /* align-items: center; */
  padding-top: 50px;
}
.header h1 {
  width: 78px;
  height: 57px;
  font-size: 50px;
  font-weight: 700;
  line-height: 57.45px;
}
.header p {
  width: 279px;
  height: 71px;
  font-weight: 300;
  font-size: 16px;
  line-height: 25px;
}
.info {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.info h1 {
  width: 150px;
  height: 23px;
  font-weight: 500;
  font-size: 20px;
  line-height: 22.98px;
}
.info ul {
  list-style: none;
}
.info li {
  margin: 20px 0;
}
.info a {
  text-decoration: none;
  color: #fff;
  font-size: 14px;
  font-weight: 300;
  line-height: 16.09px;
  text-align: start;
}
.subscribe h1 {
  font-size: 20px;
  font-weight: 500;
  line-height: 22.98px;
  font-family: "Ubuntu", sans-serif;
}
.subscribe p {
  width: 250px;
  height: 60px;
  font-weight: 300;
  font-size: 14px;
  line-height: 20px;
}
.copyright {
  height: 25px;
  font-weight: 500;
  font-size: 13px;
  text-align: center;
  margin-top: 50px;
}
label {
  position: relative;
}
input[type="text"] {
  border: none;
  width: 335px;
  height: 57px;
  border-radius: 32px;
  padding: 0 16px;
  background-color: #1e2124;
}
button {
  position: absolute;
  top: -14px;
  right: 8px;
  bottom: 0;
  width: 134px;
  height: 48px;
  background-color: #00c805;
  font-size: 14px;
  font-weight: 500;
  font-family: "Ubuntu", sans-serif;
  border: none;
  border-radius: 22.5px;
  cursor: pointer;
}
@media screen and (min-width: 100px) and (max-width: 1300px) {
  .footer {
    margin-top: 930px;
    height: 125vh;
  }
  hr {
    width: 60vw;
  }
  input[type="text"] {
    width: 70vw;
  }
}
</style>