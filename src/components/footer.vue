<template>
  <div id="footer">
    <div class="footer">
      <div class="row">
        <div class="col-4 footer-part">
          <div class="footer-heading pl-3">
            <h5><b>Products</b></h5>
          </div>
          <div class="footer-content pl-3">
            <ul>
              <li>
                <p>Living room</p>
              </li>
              <li>
                <p>Bedroom</p>
              </li>
              <li>
                <p>Drawing room</p>
              </li>
            </ul>
          </div>
        </div>

        <div class="col-4 footer-part">
          <div class="footer-heading">
            <h5><b>Conact</b></h5>
          </div>
          <div class="footer-content">
            <p>
              Sanjay Apartment, Behind Tata Service Center, Chaukaghat Water
              Tank, Chaukaghat, Varanasi</p>
              <p>
              +91 7355144324
            </p>
          </div>
        </div>

        <div class="col-4 footer-part">
          <div class="footer-heading">
            <h5><b>Navigate</b></h5>
          </div>
          <div class="footer-content">
            <ul>
              <li>
                <p>Products</p>
              </li>
              <li>
                <p>About Us</p>
              </li>
              <li>
                <p>Contact</p>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div class="social-icons">
        <div class="social">
          <a href="#"><i class="fab fa-facebook-f fa-2x"></i></a>
          <a href="#"><i class="fab fa-instagram fa-2x"></i></a>
          <!-- <i class="fab fa-twitter fa-2x"></i>
                <i class="fab fa-linkedin fa-2x"></i> -->
          <!-- <i class="fab fa-google-plus-square fa-2x"></i> -->
          <a href="mailto:brajdecoranddesigner@gmail.com"><i class="far fa-envelope fa-2x"></i></a>
          <a href="https://wa.me/918574757385" target="_blank"><i class="fab fa-whatsapp fa-2x"></i></a>
          <a href="tel:917355144324"><i class="fas fa-phone-square-alt fa-2x"></i></a>
        </div>
      </div>
      <div id="copyright">
        <p>© 2020 Braj Decor and Designer</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
/* *****************FOOTER*************** */
.footer {
  background: #17a2b8;
  /* font-size: 1rem; */
  width: 100%;
  /* position: absolute; */
  /* bottom: 0; */
  /* overflow: hidden;
        left: 0; */
  height: auto;
  padding: 2vh 0 0 3vw;
}

.footer-heading {
  /* font-size: 1rem;
  font-weight: 600; */
  text-align: center;
  margin-top: 2vh;
  margin: auto;
  /* display: inline-block; */
  width: auto;
  /* position: absolute; */
  top: 0;
}

.footer-part {
  /* position: relative;
  top: 0; */
  /* padding:2vh 0 0 3vw; */
  text-align: center;
}

.footer-heading img {
  height: 35px;
  width: 35px;
  margin-right: 10px;
}

/* .footer-heading p {
  margin-left: 10px;
  display: inline-block;
} */

.footer-content {
  /* display: inline-block; */
  /* padding-left: 3vw; */
  font-size: 15px;
}

.footer ul {
  padding: 0;
}

.row ul {
  list-style: none;
  /* margin-bottom: 5px; */
  /* border-bottom: 1px solid #000; */
}

#logo-name {
  font-size: 1rem;
  font-weight: 600;
  text-align: left;
  margin-bottom: 0.5rem;
  width: auto;
  position: relative;
  top: 0;
}

#logo-name img {
  height: 35px;
  width: 35px;
  margin-right: 10px;
  display: inline-block;
}

#logo-name p {
  display: inline-block;
}

#copyright {
  text-align: center;
  font-weight: 600;
  width: 100%;
  padding: 3px 0 3px;
  margin-top: 3vh;
  /* display: flex; */
  /* justify-content: center; */
  /* position: absolute; */
  /* bottom: 10; */
}

/* #copyright p {
  margin-right: 30px;
} */

/* #info {
  font-size: 0.7rem;
} */

/* .social-icons {
  width: 100%;
  height: 5vh;
} */

.social {
  /* margin-top: 5%; */
  width: 30%;
  margin: auto;
  /* position:absolute; */
  display: flex;
  justify-content: space-around;
}

.social a{
    color:rgb(36, 35, 35);
}
</style>