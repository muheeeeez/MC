<template>
  <div class="container">
    <header>
      <a href="#" class="logo">
        <span>MC</span>
      </a>
      <ul class="navbar" :class="{ open: isMenu }">
        <li><a href="#">Investment</a></li>
        <li><a href="#">How it works</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Key Figures</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Newsletter</a></li>
      </ul>
      <div class="main">
        <!-- <a href="#" class="user">Contact</a>
        <a href="#" class="user">Login</a> -->
        <button><a href="#" class="user">Contact Us</a></button>
        <div class="bx bx-menu" id="menu-icon" @click="toggleMenu">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="1em"
            viewBox="0 0 448 512"
          >
            <!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
            <path
              d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"
            />
          </svg>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
// let menu = document.querySelector("#menu-icon");
// let navbar = document.querySelector(".navbar");
// menu.onclick = () => {
//   navbar.classList.toggle("open");
// };
export default {
  data() {
    return {
      isMenu: false,
    };
  },
  methods: {
    toggleMenu() {
      this.isMenu = !this.isMenu;
    },
  },
};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: none;
  list-style: none;
  font-family: "Poppins", sans-serif;
}
header {
  width: 100%;
  top: 0;
  right: 0;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: transparent;
  padding: 28px 12%;
  transition: all 0.5s ease;
}
.container {
  height: 104px;
}
.logo {
  display: flex;
  align-items: center;
}
.logo svg {
  margin-right: 3px;
}
.logo span {
  font-family: "Poppins", sans-serif;
  font-size: 23px;
  font-weight: 600;
  color: #000;
  word-wrap: break-word;
}
.navbar {
  display: flex;
}
.navbar a {
  font-size: 18px;
  font-weight: 400;
  font-family: "Ubuntu", sans-serif;
  color: #000;
  word-wrap: break-word;
  padding: 5px 0;
  margin: 0px 30px;
  transition: all 0.5 ease;
}
.navbar a:hover {
  color: aqua;
}
.navbar a.active {
  color: aqua;
}
.main {
  display: flex;
}
.main a {
  margin-right: 25px;
  margin-left: 10px;
  color: #fff;
  font-size: 14px;
  font-family: "Ubuntu", sans-serif;
  font-weight: 400;
  transition: all 0.5s ease;
}
.user {
  display: flex;
  align-items: center;
  height: 47px;
}
.main button {
  padding: 5px 16px;
  border-radius: 28.5px;
  background-color: #000;
  color: #ffff;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
.main a:hover {
  color: aqua;
}
#menu-icon {
  font-size: 25px;
  margin: 7px;
  cursor: pointer;
  z-index: 10001;
  display: none;
}
@media (max-width: 1280px) {
  header {
    padding: 14px 2%;
    transition: 0.2s;
  }
  .navbar a {
    padding: 5px 0;
    margin: 0px 20px;
  }
}
@media (max-width: 1090px) {
  #menu-icon {
    display: block;
    margin: 0;
    margin-top: 15px;
    margin-left: 10px;
  }
  .navbar {
    position: absolute;
    top: 100%;
    right: 0;

    width: 270px;
    height: 29vh;
    background-color: #0000;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    border-radius: 10px;
    transition: all 0.5s ease;
  }
  .navbar a {
    display: none;
    margin: 12px 0;
    padding: 0px 25px;
    transition: all 0.5s ease;
    background-color: #0000;
  }
  .navbar.open {
    right: 2%;
    background-color: lime;
    height: max-content;
    color: #fff;
  }
}
</style>