<template>
  <div class="dropdwn">
    <nav>
      <img src="@/assets/Framelogo.svg" alt="Logo" class="img" />
      <div class="left">
        <ul>
          <li>
            <a
              class="dropdown-toggle spaced-link drop Link"
              href="#"
              id="navbarDropright"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Why Leapsail
            </a>

            <ul>
              <li>Our Goals</li>
              <li>Services</li>
              <li>Learn More</li>
            </ul>
          </li>
          <li>
            <a href="">Products</a>
          </li>
          <li>
            <a href="">Pricing</a>
          </li>
          <li>
            <a
              class="dropdown-toggle spaced-link drop Link"
              href="#"
              id="navbarDropright"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              >Learn</a
            >
            <ul>
              <li>Agency</li>
              <li>POF</li>
              <li>Visa Application</li>
            </ul>
          </li>
        </ul>
      </div>
      <div class="right">
        <ul>
          <li>
            <button class="button"><a href="#">Create Account</a></button>
          </li>
          <li>
            <a
              class="dropdown-toggle spaced-link drop Link"
              href="#"
              id="navbarDropright"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              >Support</a
            >
            <ul>
              <li>Land line</li>
              <li>Phone</li>
              <li>whatsapp</li>
            </ul>
          </li>
          <li>
            <a
              class="dropdown-toggle spaced-link drop Link"
              href="#"
              id="navbarDropright"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              >Contact</a
            >
            <ul>
              <li>Land line</li>
              <li>Phone</li>
              <li>whatsapp</li>
            </ul>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.img {
  padding: 10px 0 0 40px;
  height: auto;
  position: absolute;
  top: -13px;
  left: 20px;
  width: 190px;
}
.dropdwn {
  margin: 0 auto;
  position: sticky;
  width: 100%;
}

nav {
  height: 60px;
  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
}
nav ul li {
  display: inline-block;
  line-height: 45px;
  margin: 0 15px;
}
nav ul ul {
  
  display: none;
  
} 
.dropdown-toggle {
  background-color: #ffff;
}
/* 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 */
/* nav ul li:hover > ul {
  display: block;
} */
.left ul {
  margin-right: 30%;
}
.left ul li {
  float: left;
  display: flex;
  align-items: center;
  position: relative;
  bottom: 50px;
  justify-content: center;
  left: 15%;
  margin: 40px 0 20px 70px;
}
@media screen and (max-width: 1238px) {
  .left ul li {
    margin-right: -27px;
  }
}
@media screen and (max-width: 975px) {
  .left ul li {
    margin-right: -10px;
  }
}

.right ul li {
  float: right;
  position: relative;
  margin-left: 80px;
  display: flex;
  justify-content: center;
  align-items: center;
  top: -10px;
  right: 4%;
}
@media screen and (max-width: 1238px) {
  .right ul li {
    margin-left: -10px;
  }
}
@media screen and (max-width: 975px) {
  .right ul li {
    margin-left: -4px;
  }
}
.left ul li a {
  list-style: none;
  text-decoration: none;
  color: #333;
  font-size: 18px;
  font-weight: 400;
}
.right ul li a {
  text-decoration: none;
  color: #333;
  list-style: none;
  font-size: 18px;
  font-weight: 400;
}
nav ul li a {
  position: relative;
  font-size: 18px;
}


nav ul li a:hover {
  background-color:#f6b736;
  color:#fff;
  border-radius:10px;
  width: 120px;
text-align: center;
transition: .2s all ease-in-out;
}
/* nav ul ul li {
  width: 20%;
  float: none;
  display: list-item;
  position: fixed;
  transition:.1s all ease-in-out;
  font-size: 20px;
  color:#fff;
  z-index:400;

} */

.button {
  width: 150px;
  height: 40px;
  position: relative;
  bottom: -3px;
  background: #f6b736;
  color: #fff;
  border-radius: 20px;
  border: 2px solid #f6b736;
  cursor: pointer;
  font-size: 15px;
  font-family: "Source Sans Pro", sans-serif;
}
.button a:hover {
  color: black;
  transition: 0.5s all ease-in-out;
  border: none;
}
.button:hover {
  color: black;
  transition: 0.5s all ease-in-out;
  border-bottom: none;
}
.right ul li button a {
  color: #fff;
}
</style>
