```
CSS BASICS
```

```
code.HTML
```

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Fruit Shop Landing Page</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel="stylesheet" href="code.css" />
  </head>
  <body>
    <header id="header">
      <div class="header-content-div">
        <a href="#home-sec">
          <img
            src="https://i.ibb.co/KsztxWq/logo1.png"
            alt="Company Logo"
            id="header-img"
        /></a>
        <nav id="nav-bar">
          <a href="#about" class="nav-link">ABOUT</a>
          <a href="#varieties" class="nav-link">VARIETIES</a>
          <a href="#our-service" class="nav-link">OUR SERVICE</a>
          <a href="#benefits" class="nav-link">BENEFITS</a>
        </nav>
      </div>
    </header>
    <main>
      <section id="home-sec" class="flexible home-sec">
        <div class="eye-grabber-img">
          <img src="https://i.ibb.co/T4czpqY/apples-red-fresh-mellow-juicy-perfect-whole-on-white-desk.jpg" alt="Image of Apples" />
        </div>
        <div class="eye-grabber">
          <h1>Fresh, Crispy, Heavenly.</h1>
          <h2>
            100% Organic, vivid varieties of apples grown in Kashmir aka The
            Heaven of Earth.
          </h2>
          <button class="btn" onclick="window.location.href = '#contact';">
            Buy Now
          </button>
        </div>
      </section>
      <section id="about" class="sec-padding">
        <h3 class="section-heading">ABOUT US</h3>
        <div class="sec-content-div flexible">
          <p>
            We are a group of people with decades of experience in growing and
            selling apples. We know what a good apple looks like and how they
            are grown. This essential fruit requires a temperate climate, loamy
            soil that is rich in organic matter apart from needing proper
            drainage and aeration facilities. Lucky for us we live in Kashmir
            which is proudly known as paradise of earth is also home to
            temperate fruits like apple for which the state is very famous
            across globe. The main factor which influence temperate fruit
            bearing trees is soil, climate and environment which are highly
            favorable and unparalleled in the province of Kashmir. Kashmiri
            apples a unique look, taste, flavor, size and color.
          </p>
          <img src="https://i.ibb.co/SyKVC8M/about-img.jpg" alt="A man plucking apples from the tree" />
        </div>
      </section>
      <section id="varieties" class="sec-padding">
        <h3 class="section-heading">VARIETIES</h3>
        <div class="sec-content-div flexible">
          <div class="tile">
            <img src="https://i.ibb.co/t2x706V/amber.jpg" alt="photo of amber apples" />
            <h4>Amber</h4>
            <p>
              This red, medium-sized fruit becomes fully ripe in mid-October. It
              is mostly grown in Shopian and Kulgam.
            </p>
          </div>
          <div class="tile">
            <img
              src="https://i.ibb.co/H4Cnh7v/american-trel.png"
              alt="photo of american trel apples"
            />
            <h4>American Trel</h4>
            <p>
              A small, rounded, very crispy and sweet fruit variety that ripens
              in mid-September.
            </p>
          </div>
          <div class="tile">
            <img src="https://i.ibb.co/jTDgqYB/red-delicious.png" alt="photo of red delicious apple" />
            <h4>Red Delicious</h4>
            <p>
              A very popular and widely cultivated variety of apple that ripens
              in mid-September. Its flesh is greenish white, grainy and juicy.
            </p>
          </div>
          <div class="tile">
            <img src="https://i.ibb.co/MSvg1QN/maharaja.png" alt="photo of Maharaej apples" />
            <h4>Maharaej</h4>
            <p>
              A large apple with red and green color. It tastes a bit sour but
              sweetens with time and is available by late October.
            </p>
          </div>
          <div class="tile">
            <img src="https://i.ibb.co/zVR1LB2/hazal.png/" alt="photo of Hazratbael apples" />
            <h4>Hazratbael</h4>
            <p>
              A quickly perishable variety that ripens in early July. It is the
              oldest variety of apples cultivated in the valley and is mostly
              consumed domestically
            </p>
          </div>
          <div class="tile">
            <img src="https://i.ibb.co/BNFrnZn/golden.png" alt="photo of Golden Delicious apples" />
            <h4>Golden Delicious</h4>
            <p>
              A variety with comparatively longer shelf life, it is crispy,
              juicy and has thick greenish-white flesh which turns golden upon
              ripening. It is available till January.
            </p>
          </div>
        </div>
      </section>
      <section id="our-service" class="sec-padding">
        <h3 class="section-heading">OUR SERVICE</h3>
        <div class="sec-content-div">
          <div class="bars">
            <div class="icon-container">
              <img src="https://i.ibb.co/w6H542X/Fresh.png" alt="" />
            </div>
            <div class="txt-container">
              <h5>Fresh</h5>
              <p>We deliver fresh apples with a 100% guarantee of freshness.</p>
            </div>
          </div>
          <div class="bars">
            <div class="icon-container">
              <img src="https://i.ibb.co/FKNq4Qr/delivered.png" alt="" />
            </div>
            <div class="txt-container">
              <h5>Fast</h5>
              <p>
                We deliver your orders as fast as possible, delivery procedure
                begins as soon as apple is plucked from tree.
              </p>
            </div>
          </div>
          <div class="bars">
            <div class="icon-container">
              <img src="https://i.ibb.co/HHQK1wV/happy.png" alt="" />
            </div>
            <div class="txt-container">
              <h5>Satisfying</h5>
              <p>
                We guarantee 100% customer satisfaction. We do our best to make
                your purchase experience smooth. But if we mess up somehow you
                will get compensated for every inconvenience.
              </p>
            </div>
          </div>
        </div>
      </section>
      <section id="benefits" class="sec-padding">
        <h3 class="section-heading">BENEFITS</h3>
        <div class="sec-content-div flexible">
          <iframe
            id="video"
            width="560"
            title="Benefits of Apple"
            height="315"
            src="https://www.youtube.com/embed/W_JOJNztrnI"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </section>
      <section class="sec-padding" id="contact">
        <h3 class="section-heading">CONTACT</h3>
        <div class="sec-content-div flexible">
          <h6>To make an order or just to know more contact us :</h6>
          <form
            id="form"
            action="#"
            method="POST"
          >
            <input
              type="email"
              name="email"
              id="email"
              placeholder="Your Email Address"
              required
            />
            <input type="submit" class="btn" id="submit" value="Know More" />
          </form>
        </div>
      </section>
    </main>
  </body>
</html>
```

```
code.CSS
```

```
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,400;0,500;0,600;0,800;1,600&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap");
:root {
  font-size: 10px;
  font-family: "Open Sans", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth; 
}
body {
  margin: 0;
  padding: 0;
}
#header {
  height: max-content;
  font-family: "Montserrat", sans-serif;
  width: 100%;
  background-color: white;
  padding: 1rem 0;
  position: sticky;
  z-index: 99;
  top: 0;
  left: 0;
  box-shadow: 0 6px 31px -2px rgba(0, 0, 0, 0.1);
}
@media (max-width: 800px) {
  #header {
    text-align: center;
    height: auto;
  }
}
.header-content-div {
  max-width: 95rem;
  width: auto;
  margin: 0 auto;
}
@media (max-width: 991px) {
  .header-content-div {
    max-width: 75rem;
  }
}
#header-img {
  height: 5rem;
  width: auto;
}
@media (max-width: 800px) {
  #header-img {
    height: 4rem;
  }
}
nav {
  position: relative;
  top: 0.8rem;
  float: right;
  font-size: 1.6rem;
  font-weight: 500;
  padding: 1.5rem 0;
}
@media (max-width: 800px) {
  nav {
    position: static;
    float: none;
    font-size: 1.4rem;
    padding: 0.5rem 1rem;
  }
}
.nav-link {
  text-decoration: none;
  color: #333;
  margin: 0 0.5rem;
  padding: 0 0.6rem;
  transition: border-bottom 0.2s;
}
@media (max-width: 475px) {
  .nav-link {
    margin: 0 0.2rem;
    padding: 0 0.2rem;
    font-size: 1.2rem;
  }
}
.nav-link:hover {
  color: #e23d3d;
  border-bottom: 2px solid #e23d3d;
}
.nav-link:active {
  color: #f84848;
}
.flexible {
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: center;
  text-align: center;
}
.home-sec {
  font-family: "Montserrat", sans-serif;
  background-color: #ffffff;
  text-align: start;
  min-height: 60rem;
  height: auto;
  margin: 0 auto 5rem auto;
  justify-content: start;
  max-width: 95rem;
  color: #333;
}
@media (max-width: 800px) {
  .home-sec {
    flex-flow: column wrap;
    max-width: 100%;
  }
}
.eye-grabber {
  flex: 1;
  padding: 0 2rem;
}
@media (max-width: 800px) {
  .eye-grabber {
    max-width: max-content;
    padding-bottom: 8rem;
  }
}
.eye-grabber h1 {
  font-size: 5rem;
  line-height: 1.5;
  font-weight: 600;
}
.eye-grabber h2 {
  font-size: 2.4rem;
  font-weight: 500;
  color: #666;
}
.eye-grabber-img {
  flex: 1;
}
@media (max-width: 800px) {
  .eye-grabber-img {
    width: 100%;
  }
}
.eye-grabber-img img {
  max-width: 100%;
}
.btn {
  border: none;
  font-size: 2rem;
  border-radius: 0.4rem;
  padding: 2rem;
  background-color: #e23d3d;
  color: #fafafa;
  outline: 0;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
  transition: all 0.2s;
}

.btn:hover {
  background-color: #f84848;
  cursor: pointer;
}
.btn:active {
  transform: scale(0.9);
}
.section-heading {
  font-size: 2.5rem;
  font-family: "Montserrat", sans-serif;
  font-weight: 500;
  line-height: 1.2;
  margin: 0;
  padding: 5rem 0 5rem 0;
  text-align: center;
}
.sec-content-div {
  font-size: 2rem;
  text-align: start;
  padding: 0 2rem 5rem 2rem;
  width: auto;
  justify-content: space-around;
  max-width: 95rem;
  margin: 0 auto;
}
.sec-padding {
  padding: 8rem 0 10rem 0;
}
#about {
  background-color: #fafafa;
}
#about img {
  max-width: 100%;
  height: auto;
  background-color: white;
  border-radius: 0.5rem;
  box-shadow: 0 6px 31px -2px rgba(0, 0, 0, 0.1);
}
#varieties {
  background-color: #e3e3e3;
}
.tile {
  background-color: #fafafa;
  height: 40rem;
  width: 25rem;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
  border-radius: 0.5rem;
  transition: all 0.2s;
  padding: 1.5rem;
  margin: 1.5rem;
}
@media (max-width: 680px) {
  .tile {
    width: auto;
    max-width: 100%;
    min-width: 20rem;
    margin: 1.5rem auto;
    height: auto;
  }
}
.tile img {
  width: 100%;
  max-width: 48rem;
  border-radius: 0.5rem;
}
.tile h4 {
  font-size: 2rem;
  font-weight: 600;
  padding: 1rem 0;
  color: #e23d3d;
  margin: 0;
}
.tile p {
  font-size: 1.6rem;
  padding: 0;
  margin: 0;
}
.tile:hover {
  transform: scale(1.05);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.19), 0 16px 16px rgba(0, 0, 0, 0.23);
}
#our-service {
  background-color: #ee6f57;
}
.bars {
  height: max-content;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-content: flex-start;
  margin: 2rem;
  width: 100%;
}
@media (max-width: 990px) {
  .bars {
    flex-flow: column wrap;
  }
  .icon-container {
    margin: 0 2.5rem;
  }
}
.bars .icon-container {
  max-width: 10rem;
  flex: 1;
}
.icon-container img {
  max-height: 100%;
  max-width: 100%;
}
.bars .txt-container {
  flex: 2;
  padding: 3rem;
}
.txt-container h5 {
  font-size: 4rem;
  font-weight: 500;
  padding: 0;
  margin: 0;
  font-family: "Montserrat", sans-serif;
}
.txt-container p {
  font-size: 2.3rem;
}
#benefits {
  background-color: #f84848;
}
#benefits iframe {
  outline: 0;
  border: none;
  width:100%;
  border-radius: 0.4rem;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.19), 0 16px 16px rgba(0, 0, 0, 0.23);
}
#contact {
  background-color: #cb3737;
  color: #fafafa;
}
#contact h6 {
  font-size: 3rem;
  font-weight: 500;
}
input[type="email"] {
  border: none;
  outline: 0;
  font-size: 2rem;
  border-radius: 0.4rem;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
  padding: 2rem;
}
@media (max-width: 520px) {
  #contact h6 {
    font-size: 2rem;
  }
  #contact input[type="submit"],
  #contact input[type="email"] {
    margin: 1rem 1rem 0 1rem;
  }
}
footer {
  font-size: 1.4rem;
  background-color: #ce2f2f;
  text-align: center;
  padding: 2rem;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
  color: #fafafa;
}
footer a {
  color: #e3e3e3;
  text-decoration: none;
}
```

![alt text](op1.png) 
![alt text](op2.png) 
![alt text](op3.png) 
![alt text](op4.png) 
![alt text](op5.png)