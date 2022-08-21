<template>
  <section>
    <div class="sect">
      <div class="diagram">
        <img src="@/assets/Frame3.png" alt="BigFRame" class="work" />
      </div>
      <div class="part">
        <h2>3 steps to get you started</h2>
        <img
          src="@/assets/01.png"
          alt=""
          style="position: relative; top: 25px"
        />
        <h4>Create an account</h4>
        <h6>
          Sign up for an account with your name, best email address and phone
          number
        </h6>
        <img src="@/assets/rect.png" alt="" class="rect" />
        <img
          src="@/assets/02.png"
          alt=""
          style="position: relative; top: -20px"
        />
        <div class="pat">
          <h4>Book a slot</h4>
          <h6>You can speak with us or visit the office for appointment</h6>
        </div>
        <img
          src="@/assets/rect.png"
          alt=""
          class="rect"
          style="position: relative; top: -80px"
        />
        <img src="@/assets/03.png" alt="" />
        <div class="pa">
          <h4>Grow with Leapsail</h4>
          <h6>
            Watch your investment grow,realise your dreams and <br />
            begin your new life.
          </h6>
        </div>
      </div>
    </div>
    <div class="containee">
      <div class="airline">
        <img src="@/assets/comment.png" alt="" /> <br />
        <img src="@/assets/chat.png" alt="" /><br />
        <img src="@/assets/webinar.png" alt="" />
      </div>
      <div class="meeting">
        <img src="@/assets/meet.jpg" alt="" />
      </div>
      <div class="support">
        <h2>24/7 customer support</h2>
        <h3>
          Our team is here to give you personalized support within the hour -
          available 24/7. Join daily live webinars, watch our tutorials, or
          browse through our knowledge base
        </h3>
      </div>
    </div>
    <div class="color">
      <img src="@/assets/yellow.png" alt="" style="width: 100%" class="photo" />
      <img src="@/assets/frm.png" alt="" class="frm" />
      <div class="dtext">
        <h2>Try leapsail.com for your comfort</h2>
        <h3>Coman buy our Market| Debit card go dey needed</h3>
        <button class="get">Get Started ></button>
      </div>
    </div>
    <div class="footer">
      <div class="leap">
        <img src="@/assets/Framelogo.svg" alt="" />
        <h6 style="padding-top: 35px; font-weight: 600; font-size: 20px">
          All rights reserved &copy; Leapsail.com
        </h6>
        <p style="font-weight: 900; font-size: 20px; padding-top: 35px">
          Address
        </p>
        <p style="font-weight: 900; font-size: 20px; padding-top: 10px">
          23, Ezekiel street, Off, Toyin street Ikeja, Lagos
        </p>
        <div class="store">
          <img
            src="@/assets/apple.png"
            alt="apple"
            style="padding-top: 10px; width: 200px"
          />
          <img
            src="@/assets/google.png"
            alt="google"
            style="padding-top: 10px"
          />
        </div>
      </div>
      <div class="product">
        <h2 style="font-weight: 700">Products</h2>
        <h5>Products</h5>
        <h5>Pricing</h5>
        <h5>Partners</h5>
        <h5>Affiliate</h5>
        <h5>Students</h5>
      </div>
      <div class="team">
        <h2 style="font-weight: 700">Team</h2>
        <h5>About us</h5>
        <h5>Contact Us</h5>
        <h5>Careers</h5>
        <h5>Find a partner</h5>
        <h5>In the news</h5>
      </div>
      <div class="resources">
        <h2 style="font-weight: 700">Resources</h2>
        <h5>Knowledge base</h5>
        <h5>Guides</h5>
        <h5>Daily webinars</h5>
        <h5>Customer stores</h5>
        <h5>Video Tutorials</h5>
      </div>
      <!-- <hr style="width: 1200px; position: relative; right: -250px" /> -->
      
      <div class="below">
        <div><p>Status</p></div>
       <div> <p>Security</p></div>
        <div>   <p>Terms of service</p></div>
        <div><p>Privacy Policy</p></div>
     <div><p>Accessibilty Statement</p></div>
        <div style="display:grid; grid-template-columns:1fr 1fr;"> <img src="@/assets/web.png" alt=""> <p>English</p></div>
        <div><img src="@/assets/social.png" alt="" style="width:120px;"></div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "NextSection",
};
</script>

<style>
.containee {
  background: rgb(226, 222, 222);
  display: grid;
  grid-template-columns: 1fr 1fr 2fr;
  gap: 30px;
  z-index: 1000;
}
.footer .below {
    display: grid;
    grid-template-columns: repeat(7, 1fr);
}
.footer .below >div {
    margin: 30px 50px 40px 20px; 
    position:relative;
    right:-400px;
}
.footer .below p{
    font-size: 20px;
    font-weight:400;

}
.support h2,
h3 {
  margin-top: 40px;
  font-size: 40px;
  font-weight: 600;
}
.containee .airline {
  position: relative;
  right: -330px;
  padding-top: 50px;
}
.containee .airline img {
  padding-top: 30px;
  font-weight: 400;
  width: 60px;
}
.sect {
  background: rgb(239, 238, 238);
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  overflow: hidden;
}
.sect .diagram img {
  margin: 80px 0 0 100px;
}
.sect .part h2 {
  font-size: 60px;
  font-weight: 700;
  margin-top: 120px;
}
.sect .part h4 {
  position: relative;
  font-size: 40px;
  font-weight: 700;
  top: -40px;
}

.sect .part h6 {
  position: relative;
  right: -120px;
  top: -30px;
  font-size: 30px;
  font-weight: 400;
}
.part .pat {
  margin-top: -100px;
}
.part .pa {
  margin-top: -80px;
}
.rect {
  position: relative;
  top: -110px;
  right: -20px;
  height: 120px;
}
.meeting img {
  width: 350px;
  height: 350px;
  border-radius: 100%;
  margin-top: 50px;
  margin-bottom: 40px;
}
.color {
  position: relative;
  height: 400px;
  overflow: hidden;
}
.color .photo {
  position: absolute;
}
.color .frm {
  position: absolute;
  top: -30px;
  width: 100%;
  height: 100px;
}
.color .dtext {
  position: relative;
  top: 150px;
}

.color .dtext h2,
h3 {
  padding: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.color .dtext .get {
  position: relative;
  right: -800px;
  top: 20px;
  border: none;
  background: #fff;
  color: #f6b736;
  width: 200px;
  height: 50px;
  font-size: 25px;
  border-radius: 30px;
  font-family: "Source Sans Pro", sans-serif;
  font-weight: 700;
}
.color .dtext h2 {
  color: #fff;
  font-size: 60px;
  font-weight: 700;
}
.color .dtext h3 {
  color: #fff;
  margin-top: 5px;
  font-size: 30px;
  font-weight: 500;
}
.footer {
  background: rgb(232, 227, 227);
  display: grid;
  grid-template-columns: 3fr 1fr 1fr 1fr;
}
.footer .leap {
  margin: 50px 50px 40px 80px;
}
.footer .product h2,
h5 {
  margin: 50px 50px 20px 30px;
  padding-top: 10px;
}
.footer .team h2,
h5 {
  margin: 50px 50px 20px 30px;
  padding-top: 10px;
}
.footer .resources h2,
h5 {
  margin: 50px 50px 20px 30px;
  padding-top: 10px;
}
</style>
