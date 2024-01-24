<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Travel landing page</title>
   
    <style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Peralta&family=Poppins:wght@400;500;600;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "poppins", sans-serif;
  height: 100vh;
  width: 100%;
  overflow-x: hidden;
}

:root {
  --blue: #4b40c5;
  --orange: #ec682c;
  --white: #fff;
  --black: #000;
  --radious-card-shadow: 0px 2.4631879329681396px 4.187419891357422px 0px
      rgba(0, 0, 0, 0),
    0px 10.838027954101562px 8.67042064666748px 0px rgba(0, 0, 0, 0.01),
    0px 26.60243034362793px 17.291582107543945px 0px rgba(0, 0, 0, 0.01),
    0px 51.234317779541016px 33.893463134765625px 0px rgba(0, 0, 0, 0.01),
    0px 86.2115707397461px 62.318668365478516px 0px rgba(0, 0, 0, 0.02),
    0px 133.0121612548828px 106.40972137451172px 0px rgba(0, 0, 0, 0.02);
  --card-colom-shadow: 0px 2.4631879329681396px 4.187419891357422px 0px
      rgba(0, 0, 0, 0),
    0px 10.838027954101562px 8.67042064666748px 0px rgba(0, 0, 0, 0.01),
    0px 26.60243034362793px 17.291582107543945px 0px rgba(0, 0, 0, 0.01),
    0px 51.234317779541016px 33.893463134765625px 0px rgba(0, 0, 0, 0.01),
    0px 86.2115707397461px 62.318668365478516px 0px rgba(0, 0, 0, 0.02),
    0px 133.0121612548828px 106.40972137451172px 0px rgba(0, 0, 0, 0.02);
}

/* ? header-container design starts here  */
header {
  background: url(./img/background-img.png) no-repeat 50% center;
  background-size: cover;
  background-position: center;
  display: flex;
  flex-direction: column;
  position: relative;
  opacity: 0.9;
  overflow: hidden;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}

.logo {
  margin-top: 48px;
  margin-left: 55px;
}

.logo a {
  color: var(--black);
  font-family: Peralta;
  font-size: 40px;
  font-weight: 600;
  text-decoration: none;
}

.nav-list {
  flex: 1;
  text-align: right;
}

.nav-list ul li {
  list-style: none;
  display: inline-block;
  margin: 50px 54px 0px 13px;
}

nav ul li a {
  color: var(--1st, #212832);
  text-align: center;
  font-size: 22.612px;
  font-style: normal;
  font-weight: 700;
  text-decoration: none;
}

nav ul li .btn-orange {
  border-radius: 8px;
  border: 1px solid var(--orange);
  background: var(--orange);
  height: 40px;
  padding: 8px 20px;
  color: var(--white);
  font-size: 22.612px;
  font-weight: 400;
}

/* *text box  */

.text-box {
  text-align: start;
  margin: 180px 0px 451px 41px;
  position: relative;
  top: 125px;
}

.text-box > h1 {
  color: var(--blue);
  font-size: 48px;
  font-weight: 700;
  line-height: 118.381px;
  letter-spacing: -1.92px;
}

.text-box > h2 {
  color: var(--white);
  font-size: 32px;
  font-weight: 700;
  text-transform: uppercase;
}

.text-box > button {
  border-radius: 13.301px;
  background: #4b40c5;
  box-shadow: 0px 26.60243034362793px 46.55425262451172px 0px
    rgba(241, 165, 1, 0.15);
  color: #fff1da;
  text-align: center;
  font-family: Poppins;
  font-size: 23.942px;
  font-weight: 500;
  border: none;
  padding: 1rem;
  margin-top: 26px;
}

/* ? header-container design end here  */

/* todo main-container starts here  */
/* ? category-container starts here  */
.category-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  margin: 4rem auto;
  z-index: 500;
}

.category-container > p {
  color: var(--blue);
  font-size: 32px;
  font-weight: 700;
}

.category-container > h1 {
  color: var(--3rd, #14183e);
  font-size: 64px;
  font-weight: 700;
  text-transform: capitalize;
}

.category-cards-row {
  display: flex;
  flex-wrap: wrap;
  gap: 50px;
  margin: 6rem auto;
}

.content-card {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  text-align: center;
  align-items: center;
  width: 313.15px;
  height: 393.544px;
}

.content-card > h2 {
  color: #000;
  font-size: 24px;
  font-weight: 500;
  width: 201px;
  height: 33px;
}

.content-card > p {
  color: #000;
  font-size: 20px;
  font-weight: 400;
  line-height: 34.583px;
  width: 212px;
  height: 136px;
  margin-top: 16px;
}

.content-card > img {
  align-items: center;
}
.card-col {
  position: relative;
}
.card-col > .boder-orange {
  position: absolute;
  top: 313px;
  left: -50px;
  z-index: -1;
  width: 117.285px;
  height: 125.333px;
  border-radius: 39.904px 0px 13.301px 0px;
  background: var(--orange);
}
.card-col > .boder-blue {
  position: absolute;
  top: -30px;
  left: 225px;
  z-index: -1;
  width: 117.285px;
  height: 125.333px;
  border-radius: 0px 39.904px 0px 13.301px;
  background: #4b40c5;
}
.radious-card > .back-image {
  position: relative;
  top: -15px;
  left: 20px;
  width: 58px;
  height: 60px;
  background: rgba(240, 187, 31, 0.3);
}
.radious-card > .left-img > img {
  position: absolute;
  top: -186px;
  left: -34px;
}
.radious-card > .right-img > img {
  position: absolute;
  top: 16px;
  left: -12px;
}
.radious-card > .left-img {
  border-radius: 6.651px 13.301px 6.651px 23.942px;
}
.radious-card > .right-img {
  border-radius: 6.651px 23.942px 6.651px 13.301px;
}
.radious-card {
  border-radius: 47.884px;
  background: var(--white, --white);
  box-shadow: var(--radious-card-shadow);
}

.category-container > .orange-color {
  border-radius: 39.904px 0px 13.301px 0px;
  background: var(--orange);
  width: 117.285px;
  height: 125.333px;
  z-index: 1000;
}
/* ? category-container end here  */

/* ? topSelling-container start here  */
.topSelling-container {
  text-align: center;
}
.topSelling-container > p {
  color: var(--blue);
  text-align: center;
  font-size: 32px;
  font-weight: 700;
}
.topSelling-container > h1 {
  color: var(--3rd, #14183e);
  text-align: center;
  font-size: 62px;
  font-weight: 700;
  margin: 40px auto;
}
.row-cards {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
}
.card-colom {
  position: relative;
  width: 417.658px;
  height: 607.866px;
}
.card-colom > .img > img {
  position: absolute;
}
.card-colom > .img > .rome-img {
  top: -3px;
  left: -21px;
}
.card-colom > .img > .london-img {
  top: -3px;
  left: -106.5px;
}
.card-colom > .img > .europe-img {
  top: -3px;
  left: -106px;
}
.card-contents {
  border-radius: 0px 0px 31.923px 31.923px;
  background: var(--white, #ffffff);
  width: 418.988px;
  height: 172.916px;
  position: absolute;
  bottom: 0px;
}
.card-contents > span {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.card-contents > span > p:nth-child(1) {
  margin-left: 26.6px;
}
.card-contents > span > p:nth-child(2) {
  margin-right: 37.23px;
}
.card-contents > span > p {
  color: var(--textclr, #5e6282);
  font-size: 24px;
  font-weight: 500;
  line-height: 124.5%;
  margin-top: 35.9px;
}
.card-contents > p {
  color: var(--textclr, #5e6282);
  font-size: 20px;
  font-weight: 500;
  line-height: 124.5%;
  display: flex;
  align-items: center;
  margin-top: 24.54px;
  margin-left: 26.6px;
  gap: 18.62px;
}
/* ? topSelling-container end here  */

/* ? easySteps-container start here  */
.easySteps-container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
}
.left-content > p {
  color: var(--textclr, #5e6282);
  font-size: 23.942px;
  font-weight: 600;
  width: 204px;
  height: 32px;
  margin-left: 50.6px;
}
.left-content > h1 {
  width: 686px;
  height: 155px;
  color: var(--3rd, #14183e);
  font-size: 64px;
  font-weight: 700;
  text-transform: capitalize;
  margin-left: 41.6px;
}
.texts {
  display: flex;
  width: 529px;
  height: 87px;
  margin-top: 38px;
  margin-left: 41.6px;
  column-gap: 24.68px;
  align-items: center;
}
.texts span > h1 {
  color: var(--textclr, #5e6282);
  font-size: 24px;
  font-weight: 700;
  line-height: 124.5%;
}
.texts span > p {
  color: var(--textclr, #5e6282);
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 124.5%;
}

.background-color-blur {
  width: 424.228px;
  height: 439.807px;
  border-radius: 439.807px;
  opacity: 0.8;
  background: #4b40c5;
  filter: blur(99.75911712646484px);
  position: relative;
  top: 236.6px;
  right: 100.7px;
}
/* * small card start */
.big-card {
  position: relative;
  top: -108.4px;
  right: 175.22px;
  width: 443.402px;
  height: 479.354px;
  border-radius: 34.583px;
  background: var(--white, #fff);
  box-shadow: 0px 2.4631879329681396px 4.187419891357422px 0px rgba(0, 0, 0, 0),
    0px 10.838027954101562px 8.67042064666748px 0px rgba(0, 0, 0, 0.01),
    0px 26.60243034362793px 17.291582107543945px 0px rgba(0, 0, 0, 0.01),
    0px 51.234317779541016px 33.893463134765625px 0px rgba(0, 0, 0, 0.01),
    0px 86.2115707397461px 62.318668365478516px 0px rgba(0, 0, 0, 0.02),
    0px 133.0121612548828px 106.40972137451172px 0px rgba(0, 0, 0, 0.02);
}
.big-card > h2 {
  color: var(--black, #080809);
  font-size: 24px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: 0.36px;
  text-align: left;
  margin-left: 30.22px;
  margin-top: 31.62px;
}
.big-card > img {
  margin-top: 23.97px;
  margin-left: 29.96px;
}
.text-content {
  display: flex;
  text-align: left;
  justify-content: left;
}
.text-content > span {
  color: var(--text-2, #84829a);
  font-size: 21.282px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -0.106px;
  margin-left: 48px;
}
.text-content > p {
  color: var(--text-2, #84829a);
  font-size: 21.282px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -0.106px;
  margin-left: 29.96px;
}
.card-icons {
  align-items: center;
  margin: 8px;
}
.card-icons > span {
  background-color: #f5f5f5;
  border-radius: 50%;
  margin-left: 33.55px;
  padding: 8px;
}
.card-icons > span > img {
  width: 16.777px;
  height: 16.777px;
}
.people-going {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.people-going > span {
  display: flex;
  text-align: start;
  justify-content: left;
}
.people-going > span > .building > img {
  margin-left: 29.96px;
  margin-top: 34.74px;
  margin-bottom: 43.14px;
}
.people-going > span > p {
  color: var(--text-2, #84829a);
  font-size: 21.282px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -0.426px;
  margin: 35.95px 0px 37.69px 17.98px;
}
.people-going > img {
  margin-right: 29.96px;
  margin-bottom: 38px;
}
/* * small card end */

/* * small card start */
.small-card {
  display: flex;
  position: relative;
  top: -334px;
  left: 86px;
  align-items: flex-start;
  justify-content: left;
  width: 315.175px;
  height: 154.592px;
  border-radius: 23.942px;
  background: var(--white, #fff);
  box-shadow: 0px 2.4631879329681396px 4.187419891357422px 0px rgba(0, 0, 0, 0),
    0px 10.838027954101562px 8.67042064666748px 0px rgba(0, 0, 0, 0.01),
    0px 26.60243034362793px 17.291582107543945px 0px rgba(0, 0, 0, 0.01),
    0px 51.234317779541016px 33.893463134765625px 0px rgba(0, 0, 0, 0.01),
    0px 86.2115707397461px 62.318668365478516px 0px rgba(0, 0, 0, 0.02),
    0px 133.0121612548828px 106.40972137451172px 0px rgba(0, 0, 0, 0.02);
}
.small-card > .text-rome > p {
  color: var(--text-2, #84829a);
  font-size: 18.622px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -0.652px;
  margin-top: 19.08px;
  margin-right: 110px;
}
.small-card > .text-rome > h2 {
  color: var(--black, #080809);
  font-size: 23.942px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -0.359px;
  margin-top: 7px;
}
.small-card > .text-rome > div > p > span {
  color: var(--1, #8a79df);
  font-size: 18.622px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -1.024px;
  margin-top: 16px;
}
.small-card > .text-rome > div > p {
  color: var(--text-2, #080809);
  font-size: 18.622px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: -0.652px;
  margin-top: 16px;
}
.small-card > .icon-image > img {
  border-radius: 50%;
  margin-top: 20.37px;
  margin-left: 29.39px;
  margin-right: 12px;
}
/* * small card end */
/* ? easySteps-container end here  */

/* ? choose-container start here  */
.text-choose {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.text-choose > h1 > span {
  color: #7f2736;
  font-size: 40px;
  font-weight: 700;
  line-height: 180%;
}
.text-choose > h1 {
  color: #080809;
  font-size: 40px;
  font-weight: 700;
  line-height: 180%;
}
.text-choose > p {
  width: 858.49px;
  height: 125.398px;
  color: #2c2d32;
  text-align: center;
  font-size: 24px;
  font-weight: 400;
  line-height: 180%;
}

.choose-cards {
  display: flex;
  flex-wrap: wrap;
  text-align: center;
  justify-content: space-around;
  margin-top: 122.72px;
}
.choose-cards > .choose-card {
  position: relative;
  width: 430px;
  height: 405px;
  margin-bottom: 184px;
  border-radius: 20px;
  background: #fff;
  box-shadow: 0px 10px 60px 0px rgba(38, 45, 118, 0.08);
}
.choose-card > h1 {
  color: #000;
  text-align: center;
  font-size: 30px;
  font-weight: 500;
  width: 340px;
  height: 42px;
  margin-top: 115px;
  margin-left: 50px;
}
.choose-card > p {
  color: #000;
  font-size: 20px;
  font-weight: 400;
  line-height: 180%;
  width: 325px;
  height: 136px;
  margin-top: 30px;
  margin-left: 50px;
}
.choose-card > img {
  position: relative;
  top: -25px;
}
.choose-card > span {
  position: absolute;
  top: -50px;
  left: 167px;
  width: 96px;
  height: 94px;
  border-radius: 50%;
}
.choose-card > .blues-circle {
  background-color: #4b40c5;
}
.choose-card > .yellow-circle {
  background-color: #f0bb1f;
}
.choose-card > .orange-circle {
  background-color: #f15a2b;
}
/* ? choose-container end here  */

/* ? rectangle-container start here  */
.rectangle-content {
  position: relative;
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  text-align: center;
  margin: auto;
  margin-bottom: 195.28px;
  width: 1350.493px;
  height: 484.792px;
  border-radius: 171.586px 26.602px 26.602px 26.602px;
  background-color: #f9f7fe;
}
.rectangle-content > h2 {
  width: 991px;
  height: 161px;
  color: var(--textclr, #5e6282);
  font-size: 32px;
  font-weight: 600;
  line-height: 71.827px;
  margin-left: 194.58px;
  margin-top: 107px;
}
.rectangle-content > .email-subscribe {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
.rectangle-content > form {
  margin-top: 48.27px;
}
.rectangle-content > form > .sub-button {
  width: 207.768px;
  height: 78.49px;
  margin-right: 55.2px;
  color: white;
  font-size: 24px;
  font-weight: 400;
  border: none;
  border-radius: 13.301px;
  background: var(
    --gradient,
    linear-gradient(180deg, #ff946d 0%, #ff7d68 100%)
  );
}
.rectangle-content > form > #email {
  width: 485.947px;
  height: 78.49px;
  margin-right: 27.7px;
  flex-shrink: 0;
  border-radius: 13.301px;
  background: var(--white, #fff);
  border: none;
}
.rectangle-content > .email-subscribe > label {
  display: flex;
  align-items: center;
  left: 320px;
  position: absolute;
}
.rectangle-content > .email-subscribe > label > p {
  color: var(--textcolor, #39425d);
  font-family: Montserrat;
  font-size: 18.622px;
  font-weight: 400;
  margin-left: 15.92px;
}
.rectangle-content > .email-subscribe {
  position: relative;
}
.rectangle-content > img {
  position: absolute;
  left: auto;
  right: -33px;
}

/* ? rectangle-container end here  */
/* todo main-container end here  */

/* todo footer-container starts here  */
.footer-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  text-align: center;
  margin-bottom: 113.65px;
}
.footer-container > p {
  color: var(--textclr, #5e6282);
  font-size: 18px;
  font-weight: 500;
  line-height: 124.5%;
  text-align: start;
}
.discover-app {
  display: flex;
  flex-direction: column;
  text-align: left;
}
.discover-app > h2 {
  color: var(--textclr, #5e6282);
  font-size: 26.602px;
  font-weight: 500;
  line-height: 124.5%;
  letter-spacing: 0.133px;
  margin-top: 34.58px;
  margin-right: 86.74px;
}
.social-icons {
  margin-right: 81.31px;
}
.social-icons > span {
  position: relative;
}
.social-icons > span > .insta-icon {
  position: absolute;
  top: -40px;
  left: 33px;
}
.store-button {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 21.54px;
  margin-right: 34.76px;
}
.play-store {
  display: flex;
  align-items: center;
  width: 142.323px;
  height: 46.554px;
  border-radius: 23.277px;
  background: var(--black, #080809);
  position: relative;
}
.play-store > .logo {
  position: absolute;
  top: -38px;
  left: -27px;
}
.play-store > .text {
  position: absolute;
  left: 55px;
}
.table-content {
  display: flex;
  text-align: left;
  flex-wrap: wrap;
}
.table-content > .company {
  margin-right: 76.75px;
  margin-left: 99.74px;
}
.table-content > .contact {
  margin-right: 76.75px;
}
.table-content > .more {
  margin-right: 76.75px;
}
.contents > span > h1 {
  color: var(--black, #080809);
  font-size: 32px;
  font-weight: 700;
  line-height: 124.5%;
}
.contents > span > p {
  color: var(--textclr, #5e6282);
  font-size: 24px;
  font-weight: 500;
  line-height: 124.5%;
}
/* todo footer-container end here  */

/* todo copy rights starts here  */
.copyRights {
  color: var(--textclr, #5e6282);
  font-size: 18.622px;
  font-weight: 500;
  line-height: 124.5%;
  text-align: center;
}
/* todo copy rights end here  */

/* ! media query for responsive width in 480px  */
@media (max-width: 480px) {
  html,
  body {
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;
  }
  .nav-list {
    display: none;
  }
  .text-box {
    margin: -91px 0px 451px 41px;
    top: 250px;
  }
  .text-box > h1 {
    font-size: 33px;
    line-height: 45.381px;
    margin-bottom: 23px;
  }
  .text-box > h2 {
    font-size: 20px;
  }
  .text-box > button {
    font-size: 13.942px;
  }
  .category-container > h1 {
    font-size: 27px;
  }
  .category-container > p {
    font-size: 19px;
  }
  .category-cards-row {
    justify-content: center;
  }
  .topSelling-container > p {
    font-size: 25px;
  }
  .topSelling-container > h1 {
    font-size: 35px;
  }
  .row-cards {
    gap: 30px;
  }
  .left-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-left: -34px;
  }
  .left-content > h1 {
    font-size: 30px;
    width: auto;
    height: auto;
  }
  .easySteps-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    margin-top: 80px;
  }
  .texts {
    width: 320px;
    height: 99px;
  }
  .background-color-blur {
    right: -30.3px;
    top: 237.6px;
  }
  .big-card {
    right: -14.78px;
    left: 20.4px;
  }
  .small-card {
    top: -81px;
    left: 14px;
    width: 294.175px;
  }
  .text-choose > p {
    width: auto;
    font-size: 16px;
  }
  .text-choose > h1 {
    font-size: 35px;
  }
  .rectangle-content {
    margin: 37px;
    width: auto;
    height: 580px;
  }
  .rectangle-content > h2 {
    width: 190px;
    font-size: 21px;
    line-height: 39.827px;
    margin-left: 50.58px;
  }
  .rectangle-content > form > #email {
    width: 203.947px;
    margin-left: 30px;
  }
  .rectangle-content > .email-subscribe > label {
    left: 60px;
    top: 27px;
  }
  .rectangle-content > form > .sub-button {
    width: 198.768px;
    height: 65.49px;
    margin-top: 40px;
    margin-left: 40px;
  }
  .footer-container {
    justify-content: center;
  }
  .social-icons {
    margin-right: 20.31px;
  }
  .table-content {
    text-align: left;
    flex-direction: column;
    gap: 1rem;
  }
  .table-content > .company {
    margin-left: 0px;
  }
  .discover-app {
    align-items: stretch;
  }
  .discover-app > h2 {
    margin-left: 20px;
  }
  .logo a {
    font-size: 38px;
    margin-left: -45px;
  }
  .texts span > h1 {
    font-size: 20px;
  }
  .texts span > p {
    font-size: 15px;
    line-height: 138.5%;
  }

  .big-card {
    width: 288.402px;
  }

  .big-card > img {
    width: 230px;
    height: auto;
  }

  .right-content {
    margin-top: -250px;
  }

  .choose-cards > .choose-card {
    width: 301px;
  }
  .choose-card > span {
    left: 105px;
  }

  .choose-card > h1 {
    width: 220px;
    height: 67px;
  }
  .choose-card > p {
    font-size: 18px;
    line-height: 145%;
    width: 205px;
  }
}

/* ! media query for responsive width in 480px to 900px  */

@media (min-width: 480px) and (max-width: 912px) {
  html,
  body {
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;
  }
  .nav-list {
    display: none;
  }
  .text-box {
    margin: 111px 0px 451px 41px;
    top: 160px;
  }
  .text-box > h1 {
    line-height: 60.381px;
    font-size: 44px;
    margin-bottom: 10px;
  }
  .text-box > h2 {
    font-size: 30px;
  }
  .text-box > button {
    font-size: 20px;
  }
  .category-container > h1 {
    font-size: 47px;
    text-align: center;
  }
  .category-container > p {
    font-size: 30px;
  }
  .category-cards-row {
    justify-content: center;
  }
  .topSelling-container > p {
    font-size: 30px;
  }
  .topSelling-container > h1 {
    font-size: 47px;
  }
  .row-cards {
    gap: 50px;
  }
  .left-content {
    display: flex;
    flex-direction: column;
    margin-top: 6rem;
    gap: 30px;
  }
  .left-content > h1 {
    width: auto;
    height: auto;
    font-size: 55px;
  }
  .background-color-blur {
    top: 164.6px;
    right: -28.3px;
  }
  .big-card {
    top: -242.4px;
    right: 23.22px;
  }
  .small-card {
    top: -466px;
    left: 236px;
  }
  .text-choose > p {
    width: auto;
    margin-bottom: 43px;
  }
  .rectangle-content {
    margin: 3rem;
    margin-bottom: 195.28px;
    width: auto;
    align-items: center;
  }
  .rectangle-content > h2 {
    width: auto;
    line-height: 55.827px;
    margin-left: auto;
    font-size: 30px;
    position: absolute;
    margin-top: 70px;
    padding: 10px;
  }
  .rectangle-content > .email-subscribe {
    position: relative;
    top: 235px;
    gap: 30px;
  }
  .rectangle-content > .email-subscribe > label {
    left: 140px;
    position: absolute;
    top: 25px;
    z-index: 1;
  }
  .rectangle-content > form > #email {
    position: relative;
  }
  .footer-container {
    justify-content: center;
    gap: 3rem;
  }
}

/* ! media query for responsive width in 900px to 1480px  */

@media (min-width: 913px) and (max-width: 1480px) {
  html,
  body {
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;
  }
  .rectangle-content {
    margin: 3rem;
    margin-bottom: 195.28px;
    width: auto;
    align-items: center;
  }
  .rectangle-content > h2 {
    width: auto;
    line-height: 55.827px;
    margin-left: auto;
    font-size: 30px;
    position: absolute;
    margin-top: 70px;
    padding: 3rem;
  }
  .rectangle-content > .email-subscribe {
    position: relative;
    top: 235px;
    gap: 30px;
  }
  .rectangle-content > .email-subscribe > label {
    left: 140px;
    position: absolute;
    top: 25px;
    z-index: 1;
  }
  .rectangle-content > form > #email {
    position: relative;
  }
  .category-cards-row {
    justify-content: center;
  }
  .row-cards {
    gap: 50px;
  }
}

/* ! media query for navigation bar */

@media all and (max-width: 1390px) {
  .nav-list ul li {
    margin: 50px 35px 0px 13px;
  }
}

@media all and (max-width: 1270px) {
  .nav-list ul li {
    margin: 50px 15px 0px 13px;
  }
}
@media all and (max-width: 1271px) {
  .nav-list {
    display: none;
  }
}

/* ! media query for responsive footer  */

@media screen and (max-width: 777px) {
  .table-content {
    text-align: left;
    flex-direction: column;
    gap: 1rem;
  }
  .table-content > .company {
    margin-left: 0px;
  }
}

@media (min-width: 913px) and (max-width: 1060px) {
  .footer-container {
    justify-content: center;
    gap: 2rem;
  }
  .social-icons {
    margin-right: 58.31px;
  }
  .discover-app > h2 {
    margin-left: 20px;
  }
}
</style>
  </head>
  <body>
    
    <header>
    
      <nav>
        <div class="logo">
          <a href="ttp://guvi.com/">KV Travel.com</a>
        </div>
        <div class="nav-list">
          <ul>
            <li>
              <a href="http://" target="_blank" rel="noopener noreferrer"
                >Desitnations</a
              >
            </li>
            <li>
              <a href="http://" target="_blank" rel="noopener noreferrer"
                >Hotels</a
              >
            </li>
            <li>
              <a href="http://" target="_blank" rel="noopener noreferrer"
                >Flights</a
              >
            </li>
            <li>
              <a href="http://" target="_blank" rel="noopener noreferrer"
                >Bookings</a
              >
            </li>
            <li>
              <a
                href="http://"
                class="btn-orange"
                target="_blank"
                rel="noopener noreferrer"
                >Login</a
              >
            </li>
            <li>
              <a
                href="http://"
                class="btn-orange"
                target="_blank"
                rel="noopener noreferrer"
                >Sign up</a
              >
            </li>
          </ul>
        </div>
      </nav>
      <!-- ? text box -->
      <div class="text-box">
        <h1>Travel,enjoy and live a new and full life</h1>
        <h2>best destinations around the world</h2>
        <button type="submit">Find out more</button>
      </div>
    </header>
    <!-- todo header ends here  -->

    <!-- todo main starts here  -->
    <main>
      <!-- ? category container start -->
      <div class="category-container">
        <p>CATEGORY</p>
        <h1>We offer Best Services</h1>
        <div class="category-cards-row">
          <!-- space -->
          <div class="card-col">
            <div class="content-card">
              <img
                src="t.jpg"
                width="107.902px"
                height="97.762px"
                alt="antenna-image"
                srcset=""
              />
              <h2>Calculated Weather</h2>
              <p>As much of information possible with the weather</p>
            </div>
          </div>
          <!-- space  -->
          <div class="card-col">
            <div class="content-card radious-card">
              <span class="back-image left-img">
                <img class="plane" src="./img/airplane.svg" alt="" srcset="" />
              </span>
              <h2>Best Flights</h2>
              <p>Getting cheap best flights</p>
            </div>
            <div class="boder-orange"></div>
          </div>
          <!-- space  -->
          <div class="card-col">
            <div class="content-card radious-card">
              <span class="back-image right-img">
                <img
                  src="t1.jpg"
                  width="46.914px"
                  height="86.48px"
                  alt="#"
                  srcset=""
                />
              </span>
              <h2>Local Events</h2>
              <p>Getting good iternary based on the events</p>
            </div>
            <div class="boder-blue"></div>
          </div>
          <!-- space  -->
          <div class="card-col">
            <div class="content-card">
              <img
                src="t2.jpg"
                width="84.642px"
                height="86px"
                alt="setting-sv"
                srcset=""
              />
              <h2>Customization</h2>
              <p>We deliver outsoureced services for customers</p>
            </div>
          </div>
          <div class="orange-color"></div>
          <div class="blue-color"></div>
        </div>
      </div>
      <!-- ? category container end -->

      <!-- ? top selling container start -->
      <div class="topSelling-container">
        <p>Top Selling</p>
        <h1>Top Destinations</h1>
        <div class="row-cards">
          <!-- space  -->
          <div class="card-colom">
            <div class="img">
              <img src="./img/Rome.png" class="rome-img" alt="rome-img" />
            </div>
            <div class="card-contents">
              <span>
                <p>Rome,Italty</p>
                <p>$5,42Lakh</p>
              </span>
              <p>
                <img src="./img/arow-navigation.svg" alt="" srcset="" /> 10 Days
                Trip
              </p>
            </div>
          </div>
          <!-- space  -->
          <div class="card-colom">
            <div class="img">
              <img src="./img/London.png" class="london-img" alt="london-img" />
            </div>
            <div class="card-contents">
              <span>
                <p>London,UK</p>
                <p>$4.2Lakh</p>
              </span>
              <p>
                <img src="./img/arow-navigation.svg" alt="" srcset="" /> 12 Days
                Trip
              </p>
            </div>
          </div>
          <!-- space  -->
          <div class="card-colom">
            <div class="img">
              <img src="./img/Europe.png" class="europe-img" alt="europe-img" />
            </div>
            <div class="card-contents">
              <span>
                <p>Full Europe</p>
                <p>$15Lakh</p>
              </span>
              <p>
                <img src="./img/arow-navigation.svg" alt="" srcset="" /> 28 Days
                Trip
              </p>
            </div>
          </div>
          <!-- space  -->
        </div>
      </div>
      <!-- ? top selling container end -->

      <!-- ? 3 easy steps container start -->
      <div class="easySteps-container">
        <!-- * left side start  -->
        <div class="left-content">
          <p>Easy and Fast</p>
          <h1>Book Your Next Trip <br />In 3 Easy Steps</h1>
          <section class="section-3">
            <div class="texts">
              <img src="./img/destination.svg" alt="" srcset="" />
              <span>
                <h1>Choose Destination</h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna,
                  tortor tempus.
                </p>
              </span>
            </div>
          </section>
          <!-- space  -->
          <section class="section-3">
            <div class="texts">
              <img src="./img/payment.svg" alt="" srcset="" />
              <span>
                <h1>Make Payment</h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna,
                  tortor tempus.
                </p>
              </span>
            </div>
          </section>
          <!-- space  -->
          <section class="section-3">
            <div class="texts">
              <img src="./img/reach-airport.svg" alt="" srcset="" />
              <span>
                <h1>Reach Airport on Selected Date</h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Urna,tortor tempus.
                </p>
              </span>
            </div>
          </section>
        </div>
        <!-- *  right side start -->
        <div class="right-content">
          <div class="background-color-blur"></div>
          <div class="big-card">
            <img src="./img/greece.png" alt="" srcset="" />
            <h2>Trip To Greece</h2>
            <div class="text-content">
              <p>
                14-29<br />
                June
              </p>
              <span>|</span>
              <p style="margin-left: 6px">
                by Robbin <br />
                joseph
              </p>
            </div>
            <div class="card-icons">
              <span>
                <img src="./img/leaf.svg" alt="leaf" srcset="" />
              </span>
              <span>
                <img src="./img/map.svg" alt="map" srcset="" />
              </span>
              <span>
                <img src="./img/send.svg" alt="send" srcset="" />
              </span>
            </div>
            <div class="people-going">
              <span>
                <div class="building">
                  <img src="./img/building.svg" alt="" />
                </div>
                <p>
                  24 people <br />
                  going
                </p>
              </span>
              <img src="./img/heart.svg" alt="" srcset="" />
            </div>
          </div>
          <div class="small-card">
            <div class="icon-image">
              <img src="./img/circle-rome.png" alt="rome-circle" srcset="" />
            </div>
            <div class="text-rome">
              <p>Ongoing</p>
              <h2>Trip to rome</h2>
              <div>
                <p><span>40%</span> completed</p>
              </div>
              <img src="./img/progress-line.svg" alt="line-img" />
            </div>
          </div>
        </div>
      </div>
      <!-- ? 3 easy steps container end -->
      <!-- ? choose us container start -->
      <div class="choose-container">
        <div class="text-choose">
          <h1><span>Why</span> Choose Us</h1>
          <p>
            Larem Ipsum is Simply dummy text of the printing and typesetting
            industry.Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s.
          </p>
        </div>
        <div class="choose-cards">
          <div class="choose-card">
            <span class="radious-color blues-circle"></span>
            <img src="./img/star.svg" alt="" srcset="" />
            <h1>Handpicked Hotels</h1>
            <p>
              lorem ipsum dolor sit amet, consect adipiscing elit. Aenean
              commodo ligula eget dolor. Aenean massa
            </p>
          </div>
          <div class="choose-card">
            <span class="radious-color yellow-circle"> </span>
            <img src="./img/globle.svg" alt="" srcset="" />
            <h1>World Class Service</h1>
            <p>
              lorem ipsum dolor sit amet, consect adipiscing elit. Aenean
              commodo ligula eget dolor. Aenean massa
            </p>
          </div>
          <div class="choose-card">
            <span class="radious-color orange-circle"></span>
            <img src="./img/thumsUp.svg" alt="" srcset="" />
            <h1>Best Price Guarantee</h1>
            <p>
              lorem ipsum dolor sit amet, consect adipiscing elit. Aenean
              commodo ligula eget dolor. Aenean massa
            </p>
          </div>
        </div>
      </div>
      <!-- ? choose us container end -->
      <!-- ? rectangle input container start -->
      <div class="rectangle-container">
        <div class="rectangle-content">
          <h2>
            Subscribe to get information, latest news and other interesting
            offers at Bon Voyage
          </h2>
          <form class="email-subscribe">
            <label for="email">
              <img src="./img/mail-icon.svg" alt="email-icon" srcset="" />
              <p>Your email</p>
            </label>
            <input type="email" name="email" id="email" />
            <input type="button" class="sub-button" value="Subscribe" />
          </form>
          <img src="./img/send-icon-color.svg" alt="send-icon" />
        </div>
      </div>
      <!-- ? rectangle input container end -->
    </main>
    <!-- todo main ends here  -->

    <!-- todo footer starts here -->
    <footer>
      <div class="footer-container">
        <p>
          Book your trip in minute.get full <br />
          control for much longer.
        </p>
        <div class="table-content">
          <div class="company contents">
            <h1>Company</h1>
            <span>
              <p>About</p>
              <p>Careers</p>
              <p>Mobile</p>
            </span>
          </div>
          <div class="contact contents">
            <h1>Contact</h1>
            <span>
              <p>Help/FAQ</p>
              <p>Airlinefees</p>
              <p>Affilates</p>
            </span>
          </div>
          <div class="more contents">
            <h1>More</h1>
            <span>
              <p>Airlinefees</p>
              <p>Airline</p>
              <p>Low fare tips</p>
            </span>
          </div>
        </div>
        <div class="discover-app">
          <div class="social-icons">
            <img src="./img/face-book.svg" alt="facebook-icon" srcset="" />
            <span>
              <img src="./img/insta-bg.png" alt="instagram-icon-bg" srcset="" />
              <img
                src="./img/instagram.svg"
                class="insta-icon"
                alt="instagram-icon"
              />
            </span>
            <img src="./img/twitter.svg" alt="twitter-icon" srcset="" />
          </div>
          <h2>Discover our app</h2>
          <div class="store-button">
            <div class="play-store">
              <img
                class="logo"
                src="./img/play-store-log.svg"
                alt="palyStore-log"
                srcset=""
              />
              <img
                class="text"
                src="img/google-play.svg"
                alt="google-store-text"
                srcset=""
              />
            </div>
            <div class="apple-store">
              <img src="./img/appleStore-btn.svg" alt="" srcset="" />
            </div>
          </div>
        </div>
      </div>
    </footer>
    <!-- todo footer ends here -->
    <div class="copyRights">
      <p>All rights reserved@bonvoyage.co</p>
    </div>
  </body>
</html>
