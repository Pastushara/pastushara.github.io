<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Antools</title>

	<!-- <link rel="stylesheet" type="text/css" href="style.css"> -->

	<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.css"/>
	<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"/>

	<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.0.min.js"></script>
	<script type="text/javascript" src="https://code.jquery.com/jquery-migrate-1.2.1.min.js"></script>
	<script>

	</script>
	<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
	<style>
		@charset "UTF-8";
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
* {
  margin: 0;
  padding: 0; }

p, a {
  font-family: Poppins;
  font-size: 16px;
  color: rgba(255, 255, 255, 0.7);
  text-decoration: none; }

body {
  background: #1d242a; }

ul {
  list-style-type: none; }

h1 {
  font-size: 45px;
  font-family: Poppins;
  color: rgba(255, 255, 255, 0.9); }

h2 {
  font-size: 24px;
  font-family: Poppins;
  color: rgba(255, 255, 255, 0.8); }

h3 {
  font-size: 18px;
  font-family: Poppins;
  color: rgba(255, 255, 255, 0.7); }

.main__inner, .popular__inner, .trusted__inner, .newcomer__inner, .team__inner, .contributor__inner, .footer__inner {
  max-width: 1220px;
  margin: 0 auto; }

.main__header {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between; }
.main__logo {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  padding: 33px 0; }
  .main__logo_text {
    padding: 5px 10px; }
.main__list {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }
.main__item {
  color: rgba(255, 255, 255, 0.7);
  font-family: Poppins;
  font-size: 16px;
  padding: 35px; }
  .main__item_category:after {
    content: "⮟";
    color: rgba(255, 255, 255, 0.7); }
  .main__item_category:hover:after {
    content: "⮝";
    color: rgba(255, 255, 255, 0.7); }
  .main__item_category:hover .main__categories {
    display: block;
    position: absolute; }
.main__categories {
  display: none;
  font-size: 14px;
  color: gray; }
.main__log {
  padding: 35px 0;
  display: flex; }
  .main__log_login:hover {
    color: white;
    font-weight: 600; }
  .main__log_signup {
    background: #ff6d2e;
    border-radius: 10px;
    padding: 10px 20px;
    margin-left: 15px;
    margin-top: -10px; }
  .main__log_signup:hover {
    color: white;
    font-weight: 600; }
.main__box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }
.main__description {
  width: 50%;
  padding: 100px 0; }
  .main__description h3 {
    padding: 30px 120px 0 0; }
.main__title {
  font-size: 50px; }
.main__search {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  background: #272f35;
  padding: 10px;
  margin: 30px 0;
  border-radius: 10px;
  width: 54%; }
  .main__search input {
    background: transparent;
    border: transparent;
    margin: 0 10px;
    color: gray;
    font-size: 14px; }
  .main__search input::-webkit-input-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input::-moz-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input:-moz-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input:-ms-input-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input:focus::-webkit-input-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input:focus::-moz-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input:focus:-moz-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .main__search input:focus:-ms-input-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
.main__button {
  background: #ff6d2e;
  border-radius: 10px;
  padding: 10px 20px;
  margin-left: 10px; }
.main__button:hover {
  color: white;
  font-weight: 600; }
.main__picture {
  width: 50%; }

.popular__inner {
  margin-top: 50px; }
.popular__description {
  text-align: center;
  padding: 50px 0; }
.popular__block {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between; }
.popular__box {
  width: 30%;
  margin: 50px 0px;
  padding: 10px;
  border-radius: 20px; }
.popular__box:hover {
  margin: 45px 0 55px 0;
  background: url(img/back.png);
  -webkit-transition: 0.3s;
  transition: 0.3s; }
.popular__item {
  padding: 10px; }
.popular__price {
  color: rgba(255, 165, 56, 0.55); }
.popular__name {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }
.popular__links {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }
.popular__button {
  text-align: center;
  margin: 50px; }
.popular__load {
  color: orange;
  padding: 15px 20px;
  border: 1px solid gray;
  border-radius: 5px;
  font-size: 18px; }
.popular__load:hover {
  color: white;
  background: #ff6d2e; }

.page {
  display: none; }

.heard {
  font-size: 24px;
  margin: 3px 13px 0 10px;
  color: rgba(255, 255, 255, 0.7);
}


.heard:hover {
  color: red; }

.active {
  color: red;
  font-size: 24px;
  margin: 3px 13px 0 10px;
}

.trusted__inner {
  text-align: center;
  background: url(img/fone.png);
  margin: 200px auto; }
.trusted__description {
  padding: 40px 0 27px 0; }  
.trusted img {
  padding: 50px; }
.trusted__brands {
  display: flex;
  justify-content: space-evenly;
   padding: 50px 0;
}

.newcomer__inner {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }
.newcomer__description {
  width: 50%; }
  .newcomer__description h3 {
    padding: 30px 0 60px 0; }
.newcomer__item {
  padding: 10px; }
.newcomer__price {
  color: rgba(255, 165, 56, 0.55); }
.newcomer__link {
  background: #ff6d2e;
  border-radius: 10px;
  padding: 10px 20px; }
.newcomer__link:hover {
  color: white;
  font-weight: 600; }
.newcomer__tools {
  width: 50%; }
.newcomer__block {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between; }
.newcomer__box {
  padding: 10px;
  border-radius: 20px;
  margin: 0 10px 50px; }
.newcomer__box:hover {
  margin: -2px 10px 52px;
  background: url(img/newcomer.png);
  -webkit-transition: 0.3s;
  transition: 0.3s; }
.newcomer__name {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }
.newcomer__links {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; }

.team__inner {
  padding: 100px 0; }
.team__box {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important; }
.team__picture {
  width: 50%;
  background: url(img/circle.png);
  background-repeat: no-repeat;
  background-position: center;
  position: relative; }
.team__image {
  padding: 0 115px; }
.team__text {
  background: url(img/ronald.png);
  position: absolute;
  padding: 17px 36px;
  bottom: 26px;
  right: 80px; }
.team__description {
  position: relative;
  width: 50%; }
  .team__description p {
    padding: 140px 0;
    width: 80%; }
.team__quote {
  position: absolute;
  top: 90px; }

.slick-slider {
  display: flex;
}
button.slick-prev {
    background: transparent;
    border: none;
    color: rgba(255, 255, 255, 0.7);
}
button.slick-next {
    background: transparent;
    border: none;
    color: rgba(255, 255, 255, 0.7);
}

.slick-arrow {
  font-size: 0;
}
.slick-prev:before {
  content: "❮" !important; }

.slick-next:before {
  content: "❯" !important; }

.slick-prev:before, .slick-next:before {
  font-size: 32px !important; } 

.slick-prev:hover:before, .slick-next:hover:before {
  opacity: 1;
  color: #ff6d2e; }

.slick-dots li button::before {
  content: "¯" !important;
  font-size: 90px !important;
  margin: 0 10px 0 -20px;
  color: white !important; }

.slick-dots li {
  margin: 0 30px !important; }

.slick-dots li button:hover:before, .slick-dots li button:focus:before {
  opacity: 1;
  color: #ff6d2e !important; }

.contributor__inner {
  text-align: center;
  padding: 50px 0; }
.contributor__form {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  background: #272f35;
  padding: 10px;
  margin: 60px auto;
  border-radius: 10px;
  width: 40%; }
  .contributor__form input {
    background: transparent;
    border: transparent;
    margin: 0 10px;
    width: 70%;
    color: gray;
    font-size: 14px; }
  .contributor__form input::-webkit-input-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input::-moz-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input:-moz-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input:-ms-input-placeholder {
    opacity: 1;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input:focus::-webkit-input-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input:focus::-moz-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input:focus:-moz-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
  .contributor__form input:focus:-ms-input-placeholder {
    opacity: 0;
    -webkit-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease; }
.contributor__button {
  background: #ff6d2e;
  border-radius: 10px;
  padding: 10px 20px;
  margin-left: 10px; }
.contributor__button:hover {
  color: white;
  font-weight: 600; }

.footer {
  border-top: 1px solid #322C2C; }
  .footer__inner {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    padding: 70px 0; }
  .footer__logo {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    padding: 0 0 10px 0; }
  .footer__image {
    padding-right: 10px; }
  .footer__block {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-direction: column;
            flex-direction: column; }
  .footer__text {
    font-size: 14px; }
  .footer a, .footer h2, .footer p {
    padding: 5px 0; }

/*# sourceMappingURL=style.css.map */
	</style>
</head>
<body>
	
	<div class="main">
		<div class="main__inner">
			<div class="main__header">
				<div class="main__logo">
					<svg width="38" height="38" viewBox="0 0 38 38" fill="none" xmlns="http://www.w3.org/2000/svg">
						<rect width="38" height="38" rx="8" fill="#FF6E30"/>
						<path fill-rule="evenodd" clip-rule="evenodd" d="M19.9645 12.4359C19.632 12.4359 19.3089 12.4769 19 12.5542C19.1988 10.7606 19.9148 9.12398 20.9963 7.79492C25.2971 8.30464 28.6332 11.9646 28.6332 16.4029V22.7294C28.4605 22.7391 28.2864 22.744 28.1112 22.744C24.6706 22.744 21.6709 20.8483 20.1028 18.0423H23.9315V16.4029C23.9315 14.212 22.1554 12.4359 19.9645 12.4359Z" fill="white"/>
						<path fill-rule="evenodd" clip-rule="evenodd" d="M9.25642 16.9507C9.25642 11.625 13.5738 7.30762 18.8995 7.30762C21.5623 7.30762 23.9731 8.38695 25.7182 10.132C24.1095 8.52336 21.9351 7.48044 19.5191 7.32724C17.894 9.12575 16.9044 11.5095 16.9044 14.1243C16.9044 14.3194 16.9099 14.5131 16.9208 14.7055C16.299 15.2538 15.9068 16.0565 15.9068 16.9507V17.6157H21.8922L17.5214 17.6158C18.9445 21.4968 22.672 24.2661 27.0462 24.2661C27.5546 24.2661 28.0543 24.2287 28.5425 24.1565V28.2563H21.8922V24.2661H15.9068V28.2563H9.25642V20.9409V16.9507Z" fill="white"/>
					</svg>
					<p class="main__logo_text">antools</p>
				</div>
				<div class="main__menu">
					<ul class="main__list">
						<li class="main__item">Home</li>
						<li class="main__item main__item_category">Categories
							<ul class="main__categories">
								<li>Popular</li>
								<li>Newcomer</li> 
							</ul>
						</li>
						<li class="main__item">My collections</li>
						<li class="main__item">Blog</li>
					</ul>
				</div>
				<div class="main__log">
					<div class="main__log_login">
            <a href="#">Login</a>
          </div>
					<div class="main__log_signup">
            <a href="#">Sign Up</a>     
          </div>
				</div>
			</div>
			<div class="main__box">
				<div class="main__description">
					<h1 class="main__title">Awesome tools for Designer & Developer.</h1>
					<h3>Antool is a web collection of information on paid or free Design and Development tools</h3>
					<div class="main__search">
						<svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M11 19C15.4183 19 19 15.4183 19 11C19 6.58172 15.4183 3 11 3C6.58172 3 3 6.58172 3 11C3 15.4183 6.58172 19 11 19Z" stroke="white" stroke-opacity="0.38" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
							<path d="M21 20.9999L16.65 16.6499" stroke="white" stroke-opacity="0.38" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
						</svg>

						<input type="text" placeholder="Find more than 430+ tools">
						<a class="main__button" href="">Search</a>
					</div>
				</div>
				<div class="main__picture">
					<svg width="589" height="568" viewBox="0 0 589 568" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path opacity="0.4" d="M335.43 255.344C328.204 251.178 323.019 251.093 319.874 255.004C316.644 258.915 315.114 265.546 315.114 274.812V324.969C315.114 334.49 314.264 342.396 312.478 348.687C310.693 355.233 307.718 359.824 303.638 362.544C299.643 365.35 294.202 366.03 287.317 364.755C280.602 363.564 272.186 359.994 262.155 354.213L257.395 351.408V311.877L263.431 315.363C270.656 319.528 275.416 320.038 277.796 317.063C280.347 314.087 281.622 307.967 281.622 298.7V254.494C281.622 242.932 282.727 233.836 285.022 227.205C287.232 220.489 291.737 216.238 298.453 214.368C291.737 204.762 287.232 195.24 285.022 185.974C282.812 176.708 281.707 166.336 281.707 154.775V110.568C281.707 101.302 280.432 93.651 277.881 87.7851C275.501 82.0043 270.656 76.9886 263.516 72.823L257.48 69.3375V29.8069L262.24 32.6123C272.271 38.3931 280.687 44.599 287.402 51.1449C294.287 57.7759 299.728 64.7469 303.723 72.2279C307.888 79.709 310.863 87.7001 312.563 96.2864C314.349 104.618 315.199 113.544 315.199 123.065V173.222C315.199 182.489 316.814 190.99 319.959 198.556C323.189 206.122 328.374 212.073 335.515 216.153L335.43 255.344Z" fill="url(#paint0_linear_26_82)"/>
						<path opacity="0.4" d="M153.349 110.058C160.574 114.224 165.759 114.309 168.905 110.398C172.135 106.488 173.665 99.8568 173.665 90.5905V40.4334C173.665 30.912 174.515 23.0059 176.3 16.715C178.085 10.169 180.975 5.57839 184.971 2.77299C189.136 0.0526013 194.576 -0.627496 201.291 0.562674C208.177 1.83786 216.677 5.40837 226.708 11.2742L231.468 14.0796V53.6102L225.433 50.1247C218.207 45.9591 213.362 45.3641 210.812 48.3395C208.432 51.3999 207.242 57.5208 207.242 66.8721V111.078C207.242 122.555 206.137 131.736 203.842 138.367C201.631 145.083 197.126 149.334 190.411 151.204C197.126 160.811 201.631 170.332 203.842 179.598C206.052 188.865 207.157 199.236 207.157 210.798V255.004C207.157 264.27 208.347 271.836 210.727 277.702C213.277 283.568 218.122 288.669 225.348 292.749L231.383 296.235V335.766L226.623 332.96C216.592 327.179 208.092 320.888 201.206 314.342C194.491 307.797 189.051 300.826 184.885 293.259C180.89 285.863 178 277.872 176.3 269.371C174.515 261.04 173.665 252.114 173.665 242.592V192.435C173.665 183.169 172.05 174.668 168.905 167.101C165.674 159.535 160.489 153.585 153.349 149.504V110.058Z" fill="url(#paint1_linear_26_82)"/>
						<path opacity="0.15" d="M359.996 10.9343L539.442 114.564L539.357 544.81L359.911 441.266L359.996 10.9343Z" fill="url(#paint2_linear_26_82)"/>
						<path d="M326.249 67.2971L469.058 149.674V189.205L326.249 106.828V67.2971Z" fill="#587298"/>
						<path opacity="0.2" d="M383.373 250.329L518.701 328.455V448.067L383.373 369.941V250.329Z" fill="url(#paint3_linear_26_82)"/>
						<path opacity="0.15" d="M382.012 158.6L519.38 237.916V251.433L382.012 172.117V158.6Z" fill="white"/>
						<path opacity="0.15" d="M382.012 185.804L500.764 254.324V267.841L382.012 199.321V185.804Z" fill="white"/>
						<path opacity="0.15" d="M382.012 212.668L482.828 270.816V284.333L382.012 226.185V212.668Z" fill="white"/>
						<path opacity="0.2" d="M359.996 10.9343L539.442 114.564V172.202L359.911 68.6576L359.996 10.9343Z" fill="url(#paint4_linear_26_82)"/>
						<path opacity="0.2" d="M404.794 66.0221C404.794 74.7784 399.693 78.859 393.403 75.2034C387.113 71.5479 382.012 61.6015 382.012 52.8453C382.012 44.089 387.113 40.0084 393.403 43.6639C399.693 47.3195 404.794 57.3509 404.794 66.0221Z" fill="white"/>
						<path opacity="0.15" d="M36.6372 142.703L589 461.499L588.915 892L36.5522 573.205L36.6372 142.703Z" fill="url(#paint5_linear_26_82)"/>
						<path d="M0 248.798L142.723 331.175V370.705L0 288.414V248.798Z" fill="#EA8C4F"/>
						<path opacity="0.15" d="M73.8689 357.444L390.768 540.39V553.907L73.8689 370.961V357.444Z" fill="white"/>
						<path opacity="0.15" d="M73.8689 384.648L347.245 542.43V555.947L73.8689 398.165V384.648Z" fill="white"/>
						<path opacity="0.15" d="M73.8689 411.596L306.528 545.915V559.432L73.8689 425.113V411.596Z" fill="white"/>
						<path opacity="0.2" d="M22.0158 425.029L253.995 558.923V678.535L22.0158 544.556V425.029Z" fill="url(#paint6_linear_26_82)"/>
						<path opacity="0.15" d="M45.3922 469.15L229.683 575.5V589.017L45.3922 482.667V469.15Z" fill="white"/>
						<path opacity="0.15" d="M45.3922 496.354L192.961 581.536V595.053L45.3922 509.785V496.354Z" fill="white"/>
						<path opacity="0.2" d="M36.6368 142.703L588.235 461.159V519.477L36.6368 201.106V142.703Z" fill="url(#paint7_linear_26_82)"/>
						<path opacity="0.2" d="M96.7358 206.547C96.7358 215.304 91.6355 219.384 85.3451 215.729C79.0547 212.073 73.9544 202.127 73.9544 193.37C73.9544 184.614 79.0547 180.534 85.3451 184.189C91.6355 187.845 96.7358 197.876 96.7358 206.547Z" fill="white"/>
						<defs>
							<linearGradient id="paint0_linear_26_82" x1="384.36" y1="17.8759" x2="245.12" y2="259.239" gradientUnits="userSpaceOnUse">
								<stop stop-color="#424C57"/>
								<stop offset="0.903" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint1_linear_26_82" x1="303.984" y1="1.51234" x2="164.727" y2="242.845" gradientUnits="userSpaceOnUse">
								<stop stop-color="#414B56"/>
								<stop offset="0.903" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint2_linear_26_82" x1="542.816" y1="116.519" x2="371.208" y2="413.807" gradientUnits="userSpaceOnUse">
								<stop stop-color="white"/>
								<stop offset="1" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint3_linear_26_82" x1="476.95" y1="304.285" x2="429.254" y2="386.909" gradientUnits="userSpaceOnUse">
								<stop stop-color="white"/>
								<stop offset="1" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint4_linear_26_82" x1="421.521" y1="11.8282" x2="476.243" y2="166.739" gradientUnits="userSpaceOnUse">
								<stop stop-color="#424C58"/>
								<stop offset="1" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint5_linear_26_82" x1="405.97" y1="355.856" x2="315.072" y2="513.362" gradientUnits="userSpaceOnUse">
								<stop stop-color="white"/>
								<stop offset="1" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint6_linear_26_82" x1="163.887" y1="506.882" x2="116.192" y2="589.507" gradientUnits="userSpaceOnUse">
								<stop stop-color="#434D58"/>
								<stop offset="1" stop-color="white" stop-opacity="0"/>
							</linearGradient>
							<linearGradient id="paint7_linear_26_82" x1="173.501" y1="95.7139" x2="382.973" y2="450.519" gradientUnits="userSpaceOnUse">
								<stop stop-color="#546F94"/>
								<stop offset="1" stop-color="white" stop-opacity="0"/>
							</linearGradient>
						</defs>
					</svg>
				</div>
			</div>
		</div>
	</div>
	<div class="popular">
		<div class="popular__inner">
			<div class="popular__description">
				<h1>Most Popular Tools</h1><br>
				<h3>Tools for the best Designers and Developers <br>
				most popularly used in the world</h3>
			</div>
			<div class="popular__block">
				<div class="popular__box">
					<div class="popular__name">
						<div class="popular__item">
              <svg width="44" height="64" viewBox="0 0 44 64" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M32.6667 42.6667C38.5577 42.6667 43.3333 37.8911 43.3333 32C43.3333 26.109 38.5577 21.3334 32.6667 21.3334C26.7756 21.3334 22 26.109 22 32C22 37.8911 26.7756 42.6667 32.6667 42.6667Z" fill="#19BCFE"/>
							<path fill-rule="evenodd" clip-rule="evenodd" d="M11.3334 64C14.1624 64 16.8755 62.8761 18.8759 60.8758C20.8762 58.8754 22 56.1623 22 53.3333V42.6666H11.3334C8.50441 42.6666 5.7913 43.7904 3.79091 45.7908C1.79052 47.7912 0.666718 50.5043 0.666718 53.3333C0.666718 56.1623 1.79052 58.8754 3.79091 60.8758C5.7913 62.8761 8.50441 64 11.3334 64Z" fill="#09CF83"/>
							<path fill-rule="evenodd" clip-rule="evenodd" d="M11.3334 42.6667H22V21.3334H11.3334C8.50441 21.3334 5.7913 22.4572 3.79091 24.4576C1.79052 26.458 0.666718 29.1711 0.666718 32C0.666718 34.829 1.79052 37.5421 3.79091 39.5425C5.7913 41.5429 8.50441 42.6667 11.3334 42.6667Z" fill="#A259FF"/>
							<path fill-rule="evenodd" clip-rule="evenodd" d="M11.3334 21.3333H22V0H11.3334C8.50441 0 5.7913 1.12381 3.79091 3.12419C1.79052 5.12458 0.666718 7.83769 0.666718 10.6667C0.666718 13.4956 1.79052 16.2088 3.79091 18.2091C5.7913 20.2095 8.50441 21.3333 11.3334 21.3333Z" fill="#F24E1E"/>
							<path fill-rule="evenodd" clip-rule="evenodd" d="M32.6667 21.3333H22V0H32.6667C35.4956 0 38.2087 1.12381 40.2091 3.12419C42.2095 5.12458 43.3333 7.83769 43.3333 10.6667C43.3333 13.4956 42.2095 16.2088 40.2091 18.2091C38.2087 20.2095 35.4956 21.3333 32.6667 21.3333Z" fill="#FF7262"/>
						</svg></div>
						<div class="popular__item"><h2>FIGMA</h2>
							<h3 class="popular__price">Free</h3></div>
						</div>
						<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
						<div class="popular__links">
              <div><p class="heard">❤</p></div>
							<div class="popular__item">
                <a href="">
                  <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
								<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
							</svg></a></div>
							<div class="popular__item"><a href="">Visit</a></div>
						</div>
					</div>
					<div class="popular__box">
						<div class="popular__name">
							<div class="popular__item">
                <svg width="64" height="57" viewBox="0 0 64 57" fill="none" xmlns="http://www.w3.org/2000/svg">
								<g clip-path="url(#clip0_26_111)">
									<path d="M32 0L13.9637 1.87248L0 20.2781L32 56.867L64 20.2779L50.0365 1.87248L32 0Z" fill="#FDB300"/>
									<path d="M0 20.2782L32 56.8671L12.9615 20.2782H0Z" fill="#EB6C00"/>
									<path d="M51.0382 20.2782L32 56.8671L64 20.2782H51.0382Z" fill="#EB6C00"/>
									<path d="M12.9617 20.2782L32.0002 56.8671L51.0387 20.2782H12.9617Z" fill="#FDAD00"/>
									<path d="M13.9636 1.87248L12.9611 20.2781L31.9998 0L13.9636 1.87248Z" fill="#FDD231"/>
									<path d="M51.0382 20.2781L50.0363 1.87248L32 0L51.0382 20.2781Z" fill="#FDD231"/>
									<path d="M51.0383 20.2781H63.9998L50.0363 1.87244L51.0383 20.2781Z" fill="#FDAD00"/>
									<path d="M0 20.2781H12.9615L13.9637 1.87244L0 20.2781Z" fill="#FDAD00"/>
									<path d="M32.0002 0L12.9617 20.2779H51.0387L32.0002 0Z" fill="#FEEEB7"/>
								</g>
								<defs>
									<clipPath id="clip0_26_111">
										<rect width="64" height="56.95" fill="white"/>
									</clipPath>
								</defs>
							</svg>
						</div>
						<div class="popular__item"><h2>Sketch</h2>
							<h3 class="popular__price">Trial & Paid</h3></div>
						</div>
						<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
						<div class="popular__links">
							<div><p class="heard">❤</p></div>
							<div class="popular__item">
                <a href="">
                  <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
								<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
							</svg></a></div>
							<div class="popular__item"><a href="">Visit</a></div>
						</div>
					</div>
					<div class="popular__box">
						<div class="popular__name">
							<div class="popular__item">
                <svg width="65" height="63" viewBox="0 0 65 63" fill="none" xmlns="http://www.w3.org/2000/svg">
								<g opacity="0.78">
									<mask id="mask0_26_121" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="65" height="63">
										<path d="M45.9135 62.497C46.4286 62.6927 46.9797 62.7831 47.5322 62.7624C48.0848 62.7417 48.6271 62.6104 49.1254 62.3767L62.4557 56.1267C63.1422 55.8046 63.7215 55.3002 64.1269 54.6715C64.5323 54.0429 64.7473 53.3154 64.7472 52.573V10.1931C64.7473 9.45065 64.5323 8.72327 64.1269 8.09463C63.7215 7.46599 63.1422 6.96164 62.4557 6.63958L49.1256 0.389333C48.3724 0.0361606 47.5251 -0.0801242 46.7011 0.0565747C45.877 0.193274 45.117 0.576195 44.5261 1.15234L19.0068 23.8383L7.89074 15.6165C7.38932 15.2456 6.77047 15.0575 6.14158 15.0847C5.51268 15.112 4.91342 15.3529 4.44777 15.7657L0.882669 18.9258C-0.292917 19.9677 -0.294186 21.7698 0.879622 22.8133L10.5197 31.383L0.879622 39.9525C-0.294186 40.9963 -0.292917 42.7981 0.882669 43.8402L4.44777 47.0001C4.91339 47.4129 5.51264 47.6539 6.14153 47.6812C6.77043 47.7085 7.38929 47.5204 7.89074 47.1495L19.0068 38.9275L44.5261 61.6135C44.9207 61.9985 45.3931 62.2994 45.9135 62.497ZM48.5703 17.0609L29.2069 31.383L48.5703 45.7049V17.0609Z" fill="white"/>
									</mask>
									<g mask="url(#mask0_26_121)">
										<path d="M62.4953 6.64928L49.1545 0.390373C48.4011 0.036915 47.5535 -0.0796175 46.7291 0.0569015C45.9048 0.193421 45.1443 0.576241 44.553 1.15239L0.880099 39.9525C-0.294472 40.9963 -0.292948 42.7982 0.883145 43.8403L4.45053 47.0002C4.91657 47.4131 5.51619 47.654 6.14545 47.6813C6.77471 47.7086 7.39394 47.5205 7.89578 47.1496L60.4879 8.27301C62.2523 6.96893 64.7865 8.19508 64.7865 10.353V10.202C64.7865 9.45976 64.5715 8.73254 64.1661 8.10404C63.7608 7.47554 63.1817 6.97129 62.4953 6.64928Z" fill="#0065A9"/>
										<path d="M62.4953 56.1159L49.1545 62.3749C48.4011 62.7282 47.5535 62.8447 46.7292 62.7082C45.9048 62.5717 45.1443 62.1889 44.553 61.6128L0.880099 22.8127C-0.294472 21.7691 -0.292948 19.967 0.883145 18.9252L4.45053 15.7651C4.9166 15.3522 5.51624 15.1113 6.1455 15.084C6.77476 15.0568 7.39397 15.2449 7.89578 15.6159L60.4879 54.4922C62.2523 55.7963 64.7865 54.5701 64.7865 52.412V52.5632C64.7865 53.3055 64.5714 54.0327 64.1661 54.6612C63.7608 55.2897 63.1816 55.7939 62.4953 56.1159Z" fill="#007ACC"/>
										<path d="M49.1127 62.3798C48.359 62.733 47.5114 62.8493 46.687 62.7127C45.8625 62.5761 45.102 62.1932 44.5106 61.617C46.0038 63.0718 48.5574 62.0413 48.5574 59.9834V2.78904C48.5574 0.731112 46.0038 -0.299339 44.5106 1.15566C45.102 0.57947 45.8625 0.196552 46.6869 0.059863C47.5114 -0.0768265 48.359 0.039466 49.1127 0.392659L62.4511 6.64291C63.1379 6.96474 63.7175 7.46901 64.1231 8.09767C64.5287 8.72634 64.7439 9.45383 64.7439 10.1964V52.5765C64.7439 54.0919 63.8527 55.4734 62.4511 56.13L49.1127 62.38V62.3798Z" fill="#1F9CF0"/>
										<path d="M45.9135 62.4964C46.4287 62.6921 46.9797 62.7824 47.5322 62.7618C48.0848 62.7411 48.6271 62.6098 49.1254 62.3762L62.4554 56.1259C63.142 55.8039 63.7214 55.2996 64.1268 54.6709C64.5322 54.0423 64.7473 53.3149 64.7472 52.5724V10.1925C64.7473 9.45009 64.5323 8.72271 64.1269 8.09407C63.7215 7.46543 63.1422 6.96107 62.4557 6.63902L49.1251 0.388521C48.3719 0.0354046 47.5247 -0.0808494 46.7007 0.0558482C45.8767 0.192546 45.1167 0.575435 44.5259 1.15152L19.0068 23.8378L7.89074 15.6159C7.38932 15.2451 6.77047 15.0569 6.14158 15.0842C5.51268 15.1114 4.91342 15.3523 4.44777 15.7651L0.882669 18.9253C-0.292917 19.9671 -0.294186 21.7692 0.879622 22.8128L10.5197 31.3825L0.879622 39.9519C-0.294186 40.9957 -0.292917 42.7976 0.882669 43.8397L4.44777 46.9995C4.91339 47.4124 5.51264 47.6533 6.14153 47.6806C6.77043 47.7079 7.38929 47.5198 7.89074 47.149L19.0068 38.9269L44.5259 61.6129C44.9205 61.998 45.393 62.2989 45.9135 62.4964ZM48.5703 17.0601L29.2069 31.3825L48.5703 45.7044V17.0603V17.0601Z" fill="url(#paint0_linear_26_121)" fill-opacity="0.25"/>
									</g>
								</g>
								<defs>
									<linearGradient id="paint0_linear_26_121" x1="32.3737" y1="0.00012207" x2="32.3737" y2="62.7647" gradientUnits="userSpaceOnUse">
										<stop stop-color="white"/>
										<stop offset="1" stop-color="white" stop-opacity="0"/>
									</linearGradient>
								</defs>
							</svg>
						</div>
						<div class="popular__item"><h2>Visual Studio Code</h2>
							<h3 class="popular__price">Free</h3></div>
						</div>
						<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
						<div class="popular__links">
							<div><p class="heard">❤</p></div>
							<div class="popular__item">
                <a href="">
                  <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
								<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
							</svg></a></div>
							<div class="popular__item"><a href="">Visit</a></div>
						</div>
					</div>
				</div>
				<div class="popular__block">
					<div class="popular__box">
						<div class="popular__name">
							<div class="popular__item">
                <svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
								<g opacity="0.78">
									<path fill-rule="evenodd" clip-rule="evenodd" d="M11.432 58.4356L4.55327 49.8663C2.89826 47.8045 2 45.2692 2 42.6597V11.63C2 7.72128 5.12717 4.47794 9.16143 4.2025L41.0643 2.02437C43.382 1.86612 45.6856 2.48218 47.5895 3.76941L58.7985 11.3478C60.8049 12.7044 62 14.922 62 17.2885V52.5663C62 56.3915 58.9251 59.5586 54.9752 59.8017L19.5667 61.9813C16.4147 62.1754 13.368 60.8474 11.432 58.4356Z" fill="white"/>
									<path d="M22.4963 27.1574V26.7512C22.4963 25.7214 23.3211 24.8673 24.384 24.7964L32.1267 24.2794L42.8342 40.047V26.2083L40.0781 25.8409V25.6479C40.0781 24.6061 40.9218 23.7464 41.9983 23.6912L49.0433 23.3303V24.3442C49.0433 24.8201 48.6894 25.2272 48.2043 25.3092L46.509 25.596V48.0074L44.3813 48.7391C42.6038 49.3504 40.6249 48.696 39.6073 47.1605L29.2122 31.4744V46.4459L32.4118 47.0583L32.3672 47.355C32.2276 48.2847 31.425 48.9877 30.4541 49.0309L22.4963 49.3851C22.3911 48.3855 23.1403 47.4911 24.1739 47.3825L25.2207 47.2726V27.3105L22.4963 27.1574Z" fill="black"/>
									<path fill-rule="evenodd" clip-rule="evenodd" d="M41.3499 5.93356L9.44706 8.1117C7.5361 8.24217 6.05481 9.77849 6.05481 11.63V42.6598C6.05481 44.3994 6.65365 46.0896 7.75699 47.4641L14.6357 56.0334C15.7479 57.4189 17.4981 58.1818 19.3088 58.0703L54.7174 55.8907C56.5322 55.779 57.945 54.3239 57.945 52.5663V17.2885C57.945 16.2012 57.3959 15.1823 56.474 14.559L45.265 6.98059C44.1227 6.20825 42.7405 5.83862 41.3499 5.93356ZM11.0291 12.114C10.5853 11.7855 10.7965 11.1011 11.3539 11.0611L41.5645 8.89422C42.5271 8.82518 43.4835 9.09024 44.262 9.64176L50.3235 13.9363C50.5536 14.0993 50.4457 14.4513 50.1608 14.4668L18.1679 16.2067C17.1997 16.2594 16.244 15.9749 15.4741 15.405L11.0291 12.114ZM16.6673 21.6614C16.6673 20.6221 17.5069 19.7635 18.5807 19.7051L52.4062 17.8629C53.4527 17.8059 54.3336 18.6107 54.3336 19.6236V50.1705C54.3336 51.208 53.4969 52.0656 52.4253 52.1266L18.8139 54.0391C17.6493 54.1053 16.6673 53.2104 16.6673 52.083V21.6614Z" fill="black"/>
								</g>
							</svg></div>
							<div class="popular__item"><h2>Notion</h2>
								<h3 class="popular__price">Free & Paid</h3></div>
							</div>
							<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							<div class="popular__links">
								<div><p class="heard">❤</p></div>
								<div class="popular__item">
                  <a href="">
                    <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg></a></div>
								<div class="popular__item"><a href="">Visit</a></div>
							</div>
						</div>
						<div class="popular__box">
							<div class="popular__name">
								<div class="popular__item">
                  <svg width="65" height="64" viewBox="0 0 65 64" fill="none" xmlns="http://www.w3.org/2000/svg">
									<g opacity="0.78" clip-path="url(#clip0_32_0)">
										<path fill-rule="evenodd" clip-rule="evenodd" d="M13.6717 40.2192C13.6724 41.0975 13.4967 41.9674 13.1546 42.779C12.8125 43.5906 12.3108 44.328 11.6781 44.949C11.0454 45.57 10.2942 46.0624 9.46751 46.3979C8.6408 46.7335 7.75481 46.9057 6.86024 46.9046C5.96613 46.905 5.08072 46.7323 4.25464 46.3964C3.42855 46.0605 2.678 45.568 2.04589 44.9471C1.41379 44.3262 0.912528 43.5891 0.570777 42.7778C0.229027 41.9665 0.0534894 41.0971 0.0542014 40.2192C0.053489 39.341 0.229116 38.4714 0.571036 37.6599C0.912955 36.8485 1.41446 36.1112 2.04685 35.4903C2.67924 34.8693 3.43012 34.3769 4.25651 34.0412C5.08291 33.7054 5.96861 33.533 6.86295 33.5337H13.6744V40.2192H13.6717ZM17.0761 40.2192C17.0754 39.341 17.251 38.4714 17.5929 37.6599C17.9348 36.8485 18.4363 36.1112 19.0687 35.4903C19.7011 34.8693 20.452 34.3769 21.2784 34.0412C22.1048 33.7054 22.9905 33.533 23.8848 33.5337C24.7792 33.533 25.6649 33.7054 26.4913 34.0412C27.3177 34.3769 28.0685 34.8693 28.7009 35.4903C29.3333 36.1112 29.8348 36.8485 30.1767 37.6599C30.5187 38.4714 30.6943 39.341 30.6936 40.2192V56.9355C30.6943 57.8136 30.5187 58.6833 30.1767 59.4947C29.8348 60.3062 29.3333 61.0435 28.7009 61.6644C28.0685 62.2853 27.3177 62.7778 26.4913 63.1135C25.6649 63.4492 24.7792 63.6217 23.8848 63.621C22.9905 63.6217 22.1048 63.4492 21.2784 63.1135C20.452 62.7778 19.7011 62.2853 19.0687 61.6644C18.4363 61.0435 17.9348 60.3062 17.5929 59.4947C17.251 58.6833 17.0754 57.8136 17.0761 56.9355V40.2192Z" fill="#E01E5A"/>
										<path fill-rule="evenodd" clip-rule="evenodd" d="M23.8848 13.3736C22.9902 13.3743 22.1043 13.2018 21.2777 12.8659C20.4512 12.53 19.7002 12.0373 19.0677 11.4161C18.4353 10.7949 17.9339 10.0573 17.5921 9.24554C17.2503 8.43379 17.075 7.56384 17.076 6.68547C17.0753 5.80733 17.251 4.93766 17.5929 4.12623C17.9348 3.31479 18.4363 2.57751 19.0687 1.95657C19.7011 1.33563 20.452 0.843207 21.2784 0.507479C22.1048 0.17175 22.9905 -0.00069732 23.8848 2.11916e-06C24.7791 -0.00069732 25.6648 0.17175 26.4912 0.507479C27.3176 0.843207 28.0685 1.33563 28.7009 1.95657C29.3333 2.57751 29.8348 3.31479 30.1767 4.12623C30.5186 4.93766 30.6943 5.80733 30.6935 6.68547V13.3763H23.8875L23.8848 13.3736ZM23.8848 16.7669C24.7791 16.7662 25.6648 16.9386 26.4912 17.2743C27.3176 17.6101 28.0685 18.1025 28.7009 18.7234C29.3333 19.3444 29.8348 20.0817 30.1767 20.8931C30.5186 21.7045 30.6943 22.5742 30.6935 23.4523C30.6943 24.3305 30.5186 25.2001 30.1767 26.0116C29.8348 26.823 29.3333 27.5603 28.7009 28.1812C28.0685 28.8022 27.3176 29.2946 26.4912 29.6303C25.6648 29.9661 24.7791 30.1385 23.8848 30.1378H6.80875C5.91464 30.1385 5.02916 29.9662 4.20294 29.6306C3.37672 29.295 2.62597 28.8028 1.99361 28.1822C1.36125 27.5615 0.859694 26.8246 0.517615 26.0134C0.175536 25.2023 -0.000354061 24.3329 2.15823e-06 23.455C-0.000710178 22.5769 0.174917 21.7072 0.516837 20.8958C0.858756 20.0843 1.36026 19.347 1.99265 18.7261C2.62504 18.1052 3.37592 17.6127 4.20231 17.277C5.02871 16.9413 5.91441 16.7688 6.80875 16.7695H23.8875L23.8848 16.7669Z" fill="#36C5F0"/>
										<path fill-rule="evenodd" clip-rule="evenodd" d="M51.1738 23.4523C51.1731 22.574 51.3488 21.7041 51.6909 20.8925C52.0329 20.0809 52.5347 19.3435 53.1674 18.7225C53.8 18.1015 54.5512 17.6092 55.378 17.2736C56.2047 16.938 57.0907 16.7658 57.9852 16.7669C58.8796 16.7662 59.7653 16.9386 60.5917 17.2743C61.4181 17.6101 62.1689 18.1025 62.8013 18.7234C63.4337 19.3444 63.9352 20.0817 64.2771 20.8931C64.6191 21.7045 64.7947 22.5742 64.794 23.4523C64.7947 24.3305 64.6191 25.2002 64.2771 26.0116C63.9352 26.823 63.4337 27.5603 62.8013 28.1812C62.1689 28.8022 61.4181 29.2946 60.5917 29.6303C59.7653 29.9661 58.8796 30.1385 57.9852 30.1378H51.1738V23.455V23.4523ZM47.7694 23.4523C47.7701 24.3305 47.5945 25.2002 47.2526 26.0116C46.9106 26.823 46.4091 27.5603 45.7767 28.1812C45.1444 28.8022 44.3935 29.2946 43.5671 29.6303C42.7407 29.9661 41.855 30.1385 40.9606 30.1378C40.0661 30.1389 39.1801 29.9667 38.3534 29.6311C37.5267 29.2955 36.7755 28.8032 36.1428 28.1822C35.5101 27.5612 35.0084 26.8238 34.6663 26.0122C34.3242 25.2006 34.1485 24.3307 34.1492 23.4523V6.68548C34.1485 5.80711 34.3242 4.93722 34.6663 4.12561C35.0084 3.31401 35.5101 2.57661 36.1428 1.95563C36.7755 1.33465 37.5267 0.842289 38.3534 0.506717C39.1801 0.171145 40.0661 -0.00104452 40.9606 4.76684e-06C41.855 -0.000694672 42.7407 0.171753 43.5671 0.507481C44.3935 0.84321 45.1444 1.33563 45.7767 1.95657C46.4091 2.57752 46.9106 3.3148 47.2526 4.12623C47.5945 4.93766 47.7701 5.80733 47.7694 6.68548V23.455V23.4523Z" fill="#2EB67D"/>
										<path fill-rule="evenodd" clip-rule="evenodd" d="M40.9606 50.2474C41.8549 50.2467 42.7406 50.4191 43.567 50.7548C44.3934 51.0906 45.1443 51.583 45.7767 52.2039C46.4091 52.8249 46.9106 53.5622 47.2525 54.3736C47.5944 55.185 47.7701 56.0547 47.7693 56.9328C47.7704 57.8112 47.5951 58.6812 47.2533 59.4929C46.9115 60.3046 46.4101 61.0422 45.7777 61.6635C45.1452 62.2847 44.3942 62.7773 43.5677 63.1132C42.7411 63.4491 41.8552 63.6217 40.9606 63.621C40.066 63.6217 39.1801 63.4491 38.3535 63.1132C37.527 62.7773 36.776 62.2847 36.1435 61.6635C35.5111 61.0422 35.0097 60.3046 34.6679 59.4929C34.3261 58.6812 34.1508 57.8112 34.1518 56.9328V50.2474H40.9606ZM40.9606 46.9046C40.0663 46.9053 39.1806 46.7329 38.3542 46.3972C37.5278 46.0614 36.7769 45.569 36.1445 44.9481C35.5121 44.3271 35.0106 43.5898 34.6687 42.7784C34.3268 41.967 34.1511 41.0973 34.1518 40.2192C34.1511 39.341 34.3268 38.4714 34.6687 37.6599C35.0106 36.8485 35.5121 36.1112 36.1445 35.4903C36.7769 34.8693 37.5278 34.3769 38.3542 34.0412C39.1806 33.7054 40.0663 33.533 40.9606 33.5337H58.0366C58.931 33.533 59.8167 33.7054 60.6431 34.0412C61.4695 34.3769 62.2203 34.8693 62.8527 35.4903C63.4851 36.1112 63.9866 36.8485 64.3286 37.6599C64.6705 38.4714 64.8461 39.341 64.8454 40.2192C64.8461 41.0973 64.6705 41.967 64.3286 42.7784C63.9866 43.5898 63.4851 44.3271 62.8527 44.9481C62.2203 45.569 61.4695 46.0614 60.6431 46.3972C59.8167 46.7329 58.931 46.9053 58.0366 46.9046H40.9606Z" fill="#ECB22E"/>
									  </g>
								  	<defs>
										<clipPath id="clip0_32_0">
											<rect width="65" height="63.8231" fill="white"/>
										</clipPath>
								  	</defs>
								   </svg>
							  </div>
							<div class="popular__item"><h2>Slack</h2>
								<h3 class="popular__price">Free & Paid</h3></div>
							</div>
							<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							<div class="popular__links">
								<div><p class="heard">❤</p></div>
								<div class="popular__item">
                  <a href="">
                    <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg></a></div>
								<div class="popular__item"><a href="">Visit</a></div>
							</div>
						</div>
						<div class="popular__box">
							<div class="popular__name">
								<div class="popular__item">
                  <svg width="65" height="64" viewBox="0 0 65 64" fill="none" xmlns="http://www.w3.org/2000/svg">
									<g opacity="0.78" clip-path="url(#clip0_38_6)">
										<path d="M0 4C0 1.79086 1.79086 0 4 0H61C63.2091 0 65 1.79086 65 4V59.8234C65 62.0325 63.2091 63.8234 61 63.8234H4C1.79086 63.8234 0 62.0325 0 59.8234V4Z" fill="#FF0066"/>
										<path d="M22.1178 20.5381C24.1737 20.5087 25.819 18.8536 25.7992 16.8346C25.7792 14.8155 24.1016 13.192 22.0452 13.2017C19.9888 13.2114 18.3273 14.8506 18.327 16.8698C18.3287 17.3556 18.4283 17.8363 18.6201 18.2842C18.8119 18.732 19.092 19.1382 19.4444 19.4792C19.7968 19.8202 20.2145 20.0894 20.6733 20.2712C21.1321 20.453 21.6231 20.5438 22.1178 20.5384V20.5381Z" fill="white"/>
										<path d="M14.258 40.178C14.0429 41.0813 13.9305 42.0053 13.9229 42.9329C13.9229 46.1622 15.7063 48.3065 19.4971 48.3065C22.6405 48.3065 25.191 46.4736 27.0242 43.5123L25.9034 47.9288H32.1434L35.7134 33.8877C36.6051 30.3288 38.3314 28.4832 40.9522 28.4832C43.0139 28.4832 44.2959 29.7417 44.2959 31.8224C44.3061 32.4893 44.2121 33.154 44.0176 33.7932L42.1793 40.2496C41.9164 41.1387 41.7852 42.0604 41.7896 42.9863C41.7896 46.0498 43.6279 48.2966 47.473 48.2966C50.7621 48.2966 53.383 46.2183 54.8312 41.2376L52.3793 40.3057C51.1521 43.6449 50.0941 44.2473 49.2593 44.2473C48.4247 44.2473 47.9748 43.7013 47.9748 42.6058C47.9989 42.0311 48.0923 41.4612 48.253 40.908L50.0393 34.6154C50.4403 33.3216 50.6471 31.9773 50.653 30.625C50.653 25.9173 47.7539 23.4615 44.2413 23.4615C40.9522 23.4615 37.6088 26.3742 35.9368 29.4405L37.1614 23.9362H27.6323L26.2934 28.7868H30.7551L28.0096 39.5705C25.8514 44.2782 21.8892 44.3547 21.3925 44.245C20.576 44.0635 20.056 43.7599 20.056 42.713C20.0799 41.8656 20.2109 41.0244 20.446 40.2087L24.6268 23.9235H14.0397L12.7034 28.7741H17.1051L14.258 40.178Z" fill="white"/>
									</g>
									<defs>
										<clipPath id="clip0_38_6">
											<rect width="65" height="63.8234" fill="white"/>
										</clipPath>
									</defs>
								</svg>
							</div>
							<div class="popular__item"><h2>Invision</h2>
								<h3 class="popular__price">Free & Paid</h3></div>
							</div>
							<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							<div class="popular__links">
								<div><p class="heard">❤</p></div>
								<div class="popular__item">
                  <a href="">
									<svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg></a></div>
								<div class="popular__item"><a href="">Visit</a></div>
							</div>
						</div>
					</div>
					<div class="page">
						<div class="popular__box">
							<div class="popular__name">
								<div class="popular__item">
                  <svg width="44" height="64" viewBox="0 0 44 64" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M32.6667 42.6667C38.5577 42.6667 43.3333 37.8911 43.3333 32C43.3333 26.109 38.5577 21.3334 32.6667 21.3334C26.7756 21.3334 22 26.109 22 32C22 37.8911 26.7756 42.6667 32.6667 42.6667Z" fill="#19BCFE"/>
									<path fill-rule="evenodd" clip-rule="evenodd" d="M11.3334 64C14.1624 64 16.8755 62.8761 18.8759 60.8758C20.8762 58.8754 22 56.1623 22 53.3333V42.6666H11.3334C8.50441 42.6666 5.7913 43.7904 3.79091 45.7908C1.79052 47.7912 0.666718 50.5043 0.666718 53.3333C0.666718 56.1623 1.79052 58.8754 3.79091 60.8758C5.7913 62.8761 8.50441 64 11.3334 64Z" fill="#09CF83"/>
									<path fill-rule="evenodd" clip-rule="evenodd" d="M11.3334 42.6667H22V21.3334H11.3334C8.50441 21.3334 5.7913 22.4572 3.79091 24.4576C1.79052 26.458 0.666718 29.1711 0.666718 32C0.666718 34.829 1.79052 37.5421 3.79091 39.5425C5.7913 41.5429 8.50441 42.6667 11.3334 42.6667Z" fill="#A259FF"/>
									<path fill-rule="evenodd" clip-rule="evenodd" d="M11.3334 21.3333H22V0H11.3334C8.50441 0 5.7913 1.12381 3.79091 3.12419C1.79052 5.12458 0.666718 7.83769 0.666718 10.6667C0.666718 13.4956 1.79052 16.2088 3.79091 18.2091C5.7913 20.2095 8.50441 21.3333 11.3334 21.3333Z" fill="#F24E1E"/>
									<path fill-rule="evenodd" clip-rule="evenodd" d="M32.6667 21.3333H22V0H32.6667C35.4956 0 38.2087 1.12381 40.2091 3.12419C42.2095 5.12458 43.3333 7.83769 43.3333 10.6667C43.3333 13.4956 42.2095 16.2088 40.2091 18.2091C38.2087 20.2095 35.4956 21.3333 32.6667 21.3333Z" fill="#FF7262"/>
								</svg>
							</div>
							<div class="popular__item"><h2>FIGMA</h2>
								<h3 class="popular__price">Free</h3></div>
							</div>
							<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							<div class="popular__links">
								<div><p class="heard">❤</p></div>
								<div class="popular__item">
                  <a href="">
                    <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg></a></div>
								<div class="popular__item"><a href="">Visit</a></div>
							</div>
						</div>
						<div class="popular__box">
							<div class="popular__name">
								<div class="popular__item">
                  <svg width="64" height="57" viewBox="0 0 64 57" fill="none" xmlns="http://www.w3.org/2000/svg">
									<g clip-path="url(#clip0_26_111)">
										<path d="M32 0L13.9637 1.87248L0 20.2781L32 56.867L64 20.2779L50.0365 1.87248L32 0Z" fill="#FDB300"/>
										<path d="M0 20.2782L32 56.8671L12.9615 20.2782H0Z" fill="#EB6C00"/>
										<path d="M51.0382 20.2782L32 56.8671L64 20.2782H51.0382Z" fill="#EB6C00"/>
										<path d="M12.9617 20.2782L32.0002 56.8671L51.0387 20.2782H12.9617Z" fill="#FDAD00"/>
										<path d="M13.9636 1.87248L12.9611 20.2781L31.9998 0L13.9636 1.87248Z" fill="#FDD231"/>
										<path d="M51.0382 20.2781L50.0363 1.87248L32 0L51.0382 20.2781Z" fill="#FDD231"/>
										<path d="M51.0383 20.2781H63.9998L50.0363 1.87244L51.0383 20.2781Z" fill="#FDAD00"/>
										<path d="M0 20.2781H12.9615L13.9637 1.87244L0 20.2781Z" fill="#FDAD00"/>
										<path d="M32.0002 0L12.9617 20.2779H51.0387L32.0002 0Z" fill="#FEEEB7"/>
									</g>
									<defs>
										<clipPath id="clip0_26_111">
											<rect width="64" height="56.95" fill="white"/>
										</clipPath>
									</defs>
								</svg>
							</div>
							<div class="popular__item"><h2>Sketch</h2>
								<h3 class="popular__price">Trial & Paid</h3></div>
							</div>
							<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							<div class="popular__links">
								<div><p class="heard">❤</p></div>
								<div class="popular__item">
                  <a href="">
                    <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg></a></div>
								<div class="popular__item"><a href="">Visit</a></div>
							</div>
						</div>
						<div class="popular__box">
							<div class="popular__name">
								<div class="popular__item">
                  <svg width="65" height="63" viewBox="0 0 65 63" fill="none" xmlns="http://www.w3.org/2000/svg">
									<g opacity="0.78">
										<mask id="mask0_26_121" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="65" height="63">
											<path d="M45.9135 62.497C46.4286 62.6927 46.9797 62.7831 47.5322 62.7624C48.0848 62.7417 48.6271 62.6104 49.1254 62.3767L62.4557 56.1267C63.1422 55.8046 63.7215 55.3002 64.1269 54.6715C64.5323 54.0429 64.7473 53.3154 64.7472 52.573V10.1931C64.7473 9.45065 64.5323 8.72327 64.1269 8.09463C63.7215 7.46599 63.1422 6.96164 62.4557 6.63958L49.1256 0.389333C48.3724 0.0361606 47.5251 -0.0801242 46.7011 0.0565747C45.877 0.193274 45.117 0.576195 44.5261 1.15234L19.0068 23.8383L7.89074 15.6165C7.38932 15.2456 6.77047 15.0575 6.14158 15.0847C5.51268 15.112 4.91342 15.3529 4.44777 15.7657L0.882669 18.9258C-0.292917 19.9677 -0.294186 21.7698 0.879622 22.8133L10.5197 31.383L0.879622 39.9525C-0.294186 40.9963 -0.292917 42.7981 0.882669 43.8402L4.44777 47.0001C4.91339 47.4129 5.51264 47.6539 6.14153 47.6812C6.77043 47.7085 7.38929 47.5204 7.89074 47.1495L19.0068 38.9275L44.5261 61.6135C44.9207 61.9985 45.3931 62.2994 45.9135 62.497ZM48.5703 17.0609L29.2069 31.383L48.5703 45.7049V17.0609Z" fill="white"/>
										</mask>
										<g mask="url(#mask0_26_121)">
											<path d="M62.4953 6.64928L49.1545 0.390373C48.4011 0.036915 47.5535 -0.0796175 46.7291 0.0569015C45.9048 0.193421 45.1443 0.576241 44.553 1.15239L0.880099 39.9525C-0.294472 40.9963 -0.292948 42.7982 0.883145 43.8403L4.45053 47.0002C4.91657 47.4131 5.51619 47.654 6.14545 47.6813C6.77471 47.7086 7.39394 47.5205 7.89578 47.1496L60.4879 8.27301C62.2523 6.96893 64.7865 8.19508 64.7865 10.353V10.202C64.7865 9.45976 64.5715 8.73254 64.1661 8.10404C63.7608 7.47554 63.1817 6.97129 62.4953 6.64928Z" fill="#0065A9"/>
											<path d="M62.4953 56.1159L49.1545 62.3749C48.4011 62.7282 47.5535 62.8447 46.7292 62.7082C45.9048 62.5717 45.1443 62.1889 44.553 61.6128L0.880099 22.8127C-0.294472 21.7691 -0.292948 19.967 0.883145 18.9252L4.45053 15.7651C4.9166 15.3522 5.51624 15.1113 6.1455 15.084C6.77476 15.0568 7.39397 15.2449 7.89578 15.6159L60.4879 54.4922C62.2523 55.7963 64.7865 54.5701 64.7865 52.412V52.5632C64.7865 53.3055 64.5714 54.0327 64.1661 54.6612C63.7608 55.2897 63.1816 55.7939 62.4953 56.1159Z" fill="#007ACC"/>
											<path d="M49.1127 62.3798C48.359 62.733 47.5114 62.8493 46.687 62.7127C45.8625 62.5761 45.102 62.1932 44.5106 61.617C46.0038 63.0718 48.5574 62.0413 48.5574 59.9834V2.78904C48.5574 0.731112 46.0038 -0.299339 44.5106 1.15566C45.102 0.57947 45.8625 0.196552 46.6869 0.059863C47.5114 -0.0768265 48.359 0.039466 49.1127 0.392659L62.4511 6.64291C63.1379 6.96474 63.7175 7.46901 64.1231 8.09767C64.5287 8.72634 64.7439 9.45383 64.7439 10.1964V52.5765C64.7439 54.0919 63.8527 55.4734 62.4511 56.13L49.1127 62.38V62.3798Z" fill="#1F9CF0"/>
											<path d="M45.9135 62.4964C46.4287 62.6921 46.9797 62.7824 47.5322 62.7618C48.0848 62.7411 48.6271 62.6098 49.1254 62.3762L62.4554 56.1259C63.142 55.8039 63.7214 55.2996 64.1268 54.6709C64.5322 54.0423 64.7473 53.3149 64.7472 52.5724V10.1925C64.7473 9.45009 64.5323 8.72271 64.1269 8.09407C63.7215 7.46543 63.1422 6.96107 62.4557 6.63902L49.1251 0.388521C48.3719 0.0354046 47.5247 -0.0808494 46.7007 0.0558482C45.8767 0.192546 45.1167 0.575435 44.5259 1.15152L19.0068 23.8378L7.89074 15.6159C7.38932 15.2451 6.77047 15.0569 6.14158 15.0842C5.51268 15.1114 4.91342 15.3523 4.44777 15.7651L0.882669 18.9253C-0.292917 19.9671 -0.294186 21.7692 0.879622 22.8128L10.5197 31.3825L0.879622 39.9519C-0.294186 40.9957 -0.292917 42.7976 0.882669 43.8397L4.44777 46.9995C4.91339 47.4124 5.51264 47.6533 6.14153 47.6806C6.77043 47.7079 7.38929 47.5198 7.89074 47.149L19.0068 38.9269L44.5259 61.6129C44.9205 61.998 45.393 62.2989 45.9135 62.4964ZM48.5703 17.0601L29.2069 31.3825L48.5703 45.7044V17.0603V17.0601Z" fill="url(#paint0_linear_26_121)" fill-opacity="0.25"/>
										</g>
									</g>
									<defs>
										<linearGradient id="paint0_linear_26_121" x1="32.3737" y1="0.00012207" x2="32.3737" y2="62.7647" gradientUnits="userSpaceOnUse">
											<stop stop-color="white"/>
											<stop offset="1" stop-color="white" stop-opacity="0"/>
										</linearGradient>
									</defs>
								</svg>
							</div>
							<div class="popular__item"><h2>Visual Studio Code</h2>
								<h3 class="popular__price">Free</h3></div>
							</div>
							<p class="popular__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							<div class="popular__links">
								<div><p class="heard">❤</p></div>
								<div class="popular__item">
                  <a href="">
                    <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg></a></div>
								<div class="popular__item"><a href="">Visit</a></div>
							</div>
						</div>
					</div>
					<div class="popular__button">
						<a class="popular__load" id="load">Load more</a>
					</div>
				</div>
		</div>
		<div class="trusted">
				<div class="trusted__inner">
					<div class="trusted__description">
						<h2>Trusted more than 150+ brand</h2>
					</div>
					<div class="trusted__brands">
						<svg width="193" height="42" viewBox="0 0 193 42" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M192.953 18.8756V15.4384H188.739V10.0953L188.597 10.1396L184.639 11.366L184.561 11.39V15.4388H178.314V13.1838C178.314 12.1338 178.546 11.3297 179.003 10.7936C179.456 10.264 180.105 9.99487 180.933 9.99487C181.528 9.99487 182.144 10.1369 182.764 10.4172L182.92 10.487V6.86739L182.847 6.84029C182.268 6.62952 181.481 6.52338 180.506 6.52338C179.277 6.52338 178.16 6.79447 177.186 7.3313C176.212 7.8689 175.445 8.63636 174.908 9.61267C174.373 10.5874 174.102 11.7134 174.102 12.9593V15.4388H171.167V18.876H174.102V33.3556H178.314V18.8756H184.561V28.0774C184.561 31.8673 186.326 33.7882 189.806 33.7882C190.378 33.7882 190.98 33.7199 191.595 33.587C192.221 33.4507 192.646 33.3144 192.897 33.1686L192.953 33.1357V29.6665L192.781 29.7811C192.553 29.9361 192.268 30.0617 191.934 30.1552C191.599 30.2507 191.319 30.2988 191.102 30.2988C190.287 30.2988 189.684 30.0762 189.309 29.6371C188.93 29.1942 188.739 28.4191 188.739 27.3348V18.8756H192.953ZM161.76 30.2996C160.232 30.2996 159.026 29.7856 158.177 28.7742C157.322 27.7574 156.889 26.308 156.889 24.4665C156.889 22.567 157.322 21.0798 158.177 20.0451C159.027 19.0172 160.221 18.4957 161.726 18.4957C163.187 18.4957 164.35 18.9939 165.182 19.9771C166.019 20.966 166.444 22.441 166.444 24.3631C166.444 26.3084 166.044 27.8032 165.257 28.8028C164.474 29.7952 163.298 30.2996 161.76 30.2996ZM161.948 15.007C159.031 15.007 156.714 15.8726 155.063 17.5801C153.412 19.2879 152.575 21.6506 152.575 24.6044C152.575 27.4096 153.392 29.6661 155.004 31.3099C156.615 32.9547 158.808 33.7879 161.521 33.7879C164.349 33.7879 166.62 32.9097 168.271 31.1789C169.922 29.4493 170.758 27.1087 170.758 24.2241C170.758 21.375 169.973 19.1016 168.425 17.4686C166.875 15.8352 164.696 15.007 161.948 15.007ZM145.783 15.007C143.799 15.007 142.158 15.5209 140.904 16.5343C139.643 17.5537 139.003 18.8912 139.003 20.5094C139.003 21.3505 139.141 22.0977 139.413 22.7316C139.686 23.3673 140.11 23.927 140.672 24.397C141.23 24.8629 142.091 25.3512 143.232 25.848C144.191 26.2477 144.907 26.586 145.361 26.8525C145.806 27.1137 146.121 27.3764 146.299 27.6322C146.472 27.8823 146.56 28.2248 146.56 28.6478C146.56 29.8517 145.67 30.437 143.839 30.437C143.16 30.437 142.385 30.2938 141.536 30.0105C140.693 29.7314 139.898 29.3228 139.178 28.799L139.003 28.6723V32.7799L139.067 32.8104C139.663 33.0891 140.415 33.3236 141.3 33.5088C142.185 33.6939 142.987 33.7882 143.685 33.7882C145.838 33.7882 147.572 33.2716 148.837 32.2518C150.11 31.2255 150.756 29.8567 150.756 28.182C150.756 26.9743 150.408 25.9388 149.724 25.1034C149.044 24.2749 147.864 23.5143 146.217 22.8419C144.906 22.3089 144.066 21.8664 143.719 21.5265C143.385 21.1982 143.215 20.7343 143.215 20.1466C143.215 19.6255 143.425 19.2081 143.855 18.8698C144.288 18.53 144.891 18.3571 145.647 18.3571C146.349 18.3571 147.067 18.4693 147.781 18.6892C148.495 18.9096 149.122 19.2043 149.645 19.5648L149.817 19.6839V15.7874L149.751 15.7584C149.268 15.5488 148.632 15.3697 147.858 15.2239C147.089 15.0799 146.391 15.007 145.783 15.007ZM128.022 30.2992C126.493 30.2992 125.288 29.7856 124.438 28.7742C123.583 27.7574 123.151 26.3084 123.151 24.4665C123.151 22.567 123.584 21.0798 124.439 20.0451C125.288 19.0172 126.482 18.4957 127.988 18.4957C129.448 18.4957 130.611 18.9939 131.444 19.9771C132.28 20.966 132.705 22.441 132.705 24.3631C132.705 26.3084 132.306 27.8032 131.518 28.8028C130.736 29.7952 129.56 30.2996 128.022 30.2996V30.2992ZM128.21 15.007C125.292 15.007 122.975 15.8726 121.324 17.5801C119.674 19.2879 118.836 21.6506 118.836 24.6044C118.836 27.4107 119.654 29.6661 121.265 31.3099C122.877 32.9547 125.07 33.7879 127.783 33.7879C130.61 33.7879 132.881 32.9097 134.532 31.1789C136.183 29.4493 137.02 27.1087 137.02 24.2241C137.02 21.375 136.235 19.1016 134.686 17.4686C133.136 15.8352 130.957 15.007 128.21 15.007H128.21ZM112.442 18.5415V15.4384H108.281V33.3556H112.442V24.1905C112.442 22.6319 112.791 21.3517 113.479 20.3845C114.159 19.4288 115.064 18.9451 116.17 18.9451C116.545 18.9451 116.966 19.0073 117.421 19.1314C117.872 19.2543 118.199 19.388 118.392 19.5285L118.566 19.6568V15.4079L118.499 15.3785C118.111 15.2116 117.563 15.1276 116.869 15.1276C115.824 15.1276 114.888 15.4678 114.087 16.1379C113.383 16.7267 112.875 17.5342 112.486 18.5415H112.442H112.442ZM100.83 15.007C98.9208 15.007 97.2181 15.4216 95.7695 16.2387C94.3182 17.0577 93.1961 18.2276 92.4327 19.7148C91.6724 21.1986 91.2868 22.9312 91.2868 24.864C91.2868 26.5566 91.6607 28.1102 92.4003 29.4794C93.1403 30.8509 94.1882 31.9238 95.5139 32.6676C96.8382 33.411 98.3682 33.7882 100.063 33.7882C102.04 33.7882 103.729 33.3873 105.082 32.5981L105.137 32.566V28.7047L104.962 28.8342C104.339 29.2914 103.653 29.6532 102.926 29.9078C102.191 30.1675 101.52 30.2992 100.932 30.2992C99.3001 30.2992 97.9894 29.7814 97.0376 28.7616C96.0839 27.7399 95.6006 26.3058 95.6006 24.5005C95.6006 22.6842 96.105 21.2131 97.0987 20.1272C98.0889 19.0451 99.4018 18.496 101.001 18.496C102.369 18.496 103.701 18.9649 104.962 19.8916L105.137 20.0199V15.9516L105.08 15.9192C104.606 15.6504 103.959 15.4281 103.155 15.2598C102.356 15.0918 101.573 15.007 100.829 15.007H100.83ZM88.4204 15.4384H84.2596V33.3556H88.4208V15.4388L88.4204 15.4384ZM86.3826 7.8059C85.6981 7.8059 85.101 8.04187 84.6098 8.50998C84.1171 8.97961 83.8672 9.57029 83.8672 10.2675C83.8672 10.9536 84.1141 11.5336 84.6023 11.9902C85.087 12.4458 85.686 12.6768 86.3826 12.6768C87.0792 12.6768 87.6805 12.4458 88.1713 11.991C88.6651 11.5336 88.9158 10.9536 88.9158 10.2675C88.9158 9.59434 88.6719 9.00939 88.1916 8.52869C87.7118 8.04912 87.1034 7.8059 86.3826 7.8059ZM76.0013 14.1166V33.3556H80.2473V8.35458H74.3706L66.9002 26.9243L59.6506 8.35458H53.5342V33.3556H57.5246V14.1147H57.6618L65.317 33.3553H68.3285L75.8638 14.1166H76.001H76.0013Z" fill="white" fill-opacity="0.2"/>
							<path d="M19.574 19.8267H0V0H19.574V19.8267Z" fill="white" fill-opacity="0.2"/>
							<path d="M41.1859 19.8267H21.6122V0H41.1859V19.8267Z" fill="white" fill-opacity="0.2"/>
							<path d="M19.5733 41.7251H0V21.8988H19.5733V41.7251Z" fill="white" fill-opacity="0.2"/>
							<path d="M41.1859 41.7251H21.6122V21.8988H41.1859V41.7251Z" fill="white" fill-opacity="0.2"/>
						</svg>

						<svg width="157" height="51" viewBox="0 0 157 51" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M152.11 31.1682L156.466 34.0427C155.052 36.104 151.671 39.6406 145.825 39.6406C138.567 39.6406 133.161 34.0807 133.161 27.0078C133.161 19.4813 138.624 14.3752 145.214 14.3752C151.843 14.3752 155.09 19.5945 156.141 22.4123L156.714 23.8497L139.637 30.8467C140.935 33.3809 142.961 34.6669 145.825 34.6669C148.691 34.6669 150.677 33.2674 152.11 31.1682ZM138.72 26.611L150.124 21.9208C149.493 20.3514 147.621 19.2357 145.386 19.2357C142.54 19.2357 138.586 21.732 138.72 26.611Z" fill="white" fill-opacity="0.2"/>
							<path d="M124.927 1.49686H130.428V38.487H124.927V1.49655V1.49686Z" fill="white" fill-opacity="0.2"/>
							<path d="M116.255 15.3586H121.565V37.825C121.565 47.148 116.007 50.987 109.435 50.987C103.246 50.987 99.5216 46.8645 98.1269 43.5173L102.998 41.5125C103.876 43.5737 105.997 46.0135 109.435 46.0135C113.657 46.0135 116.255 43.4226 116.255 38.5815V36.7661H116.064C114.803 38.2788 112.396 39.6404 109.34 39.6404C102.96 39.6404 97.1141 34.1372 97.1141 27.0458C97.1141 19.9161 102.96 14.3565 109.34 14.3565C112.377 14.3565 114.803 15.6992 116.064 17.1743H116.255V15.3589V15.3586ZM116.637 27.0458C116.637 22.5827 113.638 19.3299 109.817 19.3299C105.959 19.3299 102.711 22.5827 102.711 27.0458C102.711 31.4518 105.959 34.6478 109.817 34.6478C113.638 34.667 116.637 31.4518 116.637 27.0458H116.637Z" fill="white" fill-opacity="0.2"/>
							<path d="M66.9136 26.9512C66.9136 34.232 61.1831 39.5837 54.1533 39.5837C47.1239 39.5837 41.3931 34.2132 41.3931 26.9512C41.3931 19.6327 47.1239 14.2998 54.1533 14.2998C61.1831 14.2998 66.9136 19.6327 66.9136 26.9512ZM61.3358 26.9512C61.3358 22.4128 58.0118 19.2921 54.1533 19.2921C50.2949 19.2921 46.9709 22.4128 46.9709 26.9512C46.9709 31.4519 50.2949 34.6103 54.1533 34.6103C58.0121 34.6103 61.3358 31.4519 61.3358 26.9512Z" fill="white" fill-opacity="0.2"/>
							<path d="M94.7841 27.0078C94.7841 34.2886 89.0533 39.6403 82.0238 39.6403C74.9941 39.6403 69.2636 34.2883 69.2636 27.0078C69.2636 19.6893 74.9941 14.3752 82.0238 14.3752C89.0533 14.3752 94.7841 19.6704 94.7841 27.0078ZM89.187 27.0078C89.187 22.4694 85.8633 19.3487 82.0045 19.3487C78.1461 19.3487 74.8221 22.4694 74.8221 27.0078C74.8221 31.5085 78.1461 34.6669 82.0045 34.6669C85.8823 34.6669 89.187 31.4897 89.187 27.0078Z" fill="white" fill-opacity="0.2"/>
							<path d="M20.4189 34.0995C12.4149 34.0995 6.14965 27.7075 6.14965 19.7837C6.14965 11.8602 12.4149 5.46819 20.4189 5.46819C24.7361 5.46819 27.8877 7.15119 30.2182 9.30715L34.0579 5.50613C30.8106 2.42367 26.4744 0.0782776 20.4189 0.0782776C9.45431 0.0785812 0.227806 8.9292 0.227806 19.7837C0.227806 30.6388 9.45431 39.4891 20.4189 39.4891C26.3407 39.4891 30.8106 37.5602 34.3063 33.9672C37.8974 30.4117 39.0053 25.4192 39.0053 21.3723C39.0053 20.1052 38.8526 18.8004 38.6805 17.836H20.4189V23.0932H33.4275C33.0454 26.384 31.9949 28.6343 30.4475 30.1658C28.5755 32.0383 25.6149 34.0995 20.4189 34.0995Z" fill="white" fill-opacity="0.2"/>
						</svg>

						<svg width="194" height="49" viewBox="0 0 194 49" fill="none" xmlns="http://www.w3.org/2000/svg">
							<g clip-path="url(#clip0_43_18)">
								<path d="M61.9865 38.4028L64.4065 32.8112C67.0217 34.7527 70.4955 35.7625 73.9307 35.7625C76.4679 35.7625 78.0684 34.7915 78.0684 33.3162C78.0293 29.2002 62.8841 32.4229 62.767 22.0941C62.728 16.8522 67.4124 12.8139 74.0478 12.8139C77.9903 12.8139 81.9328 13.7845 84.7432 15.9977L82.4792 21.7059C79.903 20.0749 76.7024 18.9102 73.6575 18.9102C71.5887 18.9102 70.2227 19.8808 70.2227 21.1235C70.2618 25.1619 85.5241 22.9486 85.6802 32.8112C85.6802 38.1699 81.1133 41.9365 74.5555 41.9365C69.754 41.9365 65.3432 40.8102 61.9865 38.4028V38.4028ZM154.849 30.792L161.524 34.4809C159.025 38.9463 154.263 41.9365 148.759 41.9365C140.679 41.9365 134.121 35.4131 134.121 27.3752C134.121 19.3373 140.679 12.8139 148.759 12.8139C154.224 12.8139 159.025 15.8425 161.524 20.2694L154.849 23.958C153.639 21.8612 151.375 20.4247 148.759 20.4247C144.895 20.4247 141.772 23.5309 141.772 27.3752C141.772 31.2194 144.895 34.3256 148.759 34.3256C151.375 34.3256 153.639 32.8888 154.848 30.792H154.849ZM89.0369 0.73764H97.3903V41.3926H89.0369V0.73764V0.73764ZM164.802 0.73764H173.156V24.618L182.602 13.3962H192.829L181.158 26.9089L193.766 41.3926H183.071L173.156 29.2002V41.3926H164.802V0.73764ZM122.216 30.87V23.9968C121.006 21.9776 118.508 20.4247 115.698 20.4247C111.833 20.4247 108.711 23.5309 108.711 27.3752C108.711 31.2194 111.833 34.3256 115.698 34.3256C118.508 34.3256 121.006 32.85 122.216 30.8696V30.87ZM122.216 13.3966H130.57V41.3541H122.216V38.0538C120.85 40.3447 117.454 41.9368 113.902 41.9368C106.563 41.9368 100.786 35.4134 100.786 27.3367C100.786 19.26 106.563 12.8143 113.902 12.8143C117.454 12.8143 120.85 14.4064 122.216 16.6973V13.3958V13.3966Z" fill="white" fill-opacity="0.2"/>
								<path d="M10.3442 30.8308C10.3442 33.6652 8.04122 35.9566 5.19146 35.9566C4.51463 35.9572 3.84431 35.8251 3.21888 35.5677C2.59345 35.3103 2.02519 34.9328 1.54661 34.4567C1.06803 33.9806 0.688547 33.4152 0.429868 32.7931C0.171189 32.1709 0.0383979 31.5041 0.0390958 30.8308C0.0390958 27.9963 2.34209 25.7054 5.19146 25.7054H10.3442V30.8308ZM12.9204 30.8308C12.9204 27.9963 15.2234 25.7054 18.0728 25.7054C20.9221 25.7054 23.2255 27.9963 23.2255 30.8308V43.6447C23.2255 46.4791 20.9225 48.7704 18.0728 48.7704C17.396 48.771 16.7257 48.6389 16.1003 48.3815C15.4749 48.1241 14.9067 47.7465 14.4282 47.2704C13.9496 46.7943 13.5702 46.229 13.3115 45.6069C13.0529 44.9847 12.9201 44.3179 12.9208 43.6447V30.8308H12.9204Z" fill="white" fill-opacity="0.2"/>
								<path d="M18.0727 10.2512C17.3959 10.2518 16.7256 10.1196 16.1002 9.8622C15.4748 9.6048 14.9066 9.22725 14.4281 8.75115C13.9496 8.27505 13.5701 7.70975 13.3114 7.0876C13.0528 6.46544 12.92 5.79866 12.9207 5.1254C12.9203 2.29094 15.2233 0 18.0727 0C20.9221 0 23.2254 2.29094 23.2254 5.1254V10.2512H18.0727V10.2512ZM18.0727 12.8527C20.9221 12.8527 23.2254 15.1436 23.2254 17.9781C23.2254 20.8126 20.9224 23.1039 18.0727 23.1039H5.15237C4.47554 23.1045 3.80522 22.9724 3.17979 22.715C2.55436 22.4576 1.98609 22.0801 1.50752 21.604C1.02894 21.1279 0.649454 20.5626 0.390775 19.9404C0.132096 19.3182 -0.000695083 18.6514 2.73605e-06 17.9781C2.73605e-06 15.1436 2.30299 12.8531 5.15237 12.8531H18.0731L18.0727 12.8527Z" fill="white" fill-opacity="0.2"/>
								<path d="M38.7219 17.9781C38.7219 15.1436 41.0249 12.8527 43.8743 12.8527C46.7236 12.8527 49.027 15.1436 49.027 17.9781C49.027 20.8126 46.724 23.1039 43.8743 23.1039H38.7219V17.9781V17.9781ZM36.1453 17.9781C36.1453 20.8126 33.8427 23.1039 30.993 23.1039C30.3161 23.1045 29.6458 22.9724 29.0204 22.715C28.395 22.4576 27.8267 22.0801 27.3481 21.604C26.8696 21.1279 26.4901 20.5626 26.2314 19.9404C25.9727 19.3182 25.8399 18.6514 25.8406 17.9781V5.1254C25.8406 2.29094 28.1436 0 30.993 0C33.8424 0 36.1457 2.29094 36.1457 5.1254V17.9785L36.1453 17.9781Z" fill="white" fill-opacity="0.2"/>
								<path d="M30.993 38.5193C33.8424 38.5193 36.1457 40.8102 36.1457 43.6447C36.1457 46.4791 33.8427 48.7704 30.993 48.7704C30.3161 48.7711 29.6458 48.6389 29.0204 48.3816C28.395 48.1242 27.8267 47.7467 27.3481 47.2706C26.8696 46.7944 26.4901 46.2291 26.2314 45.6069C25.9727 44.9848 25.8399 44.318 25.8406 43.6447V38.5193H30.993V38.5193ZM30.993 35.9562C30.3162 35.9568 29.6459 35.8247 29.0205 35.5674C28.3951 35.31 27.8268 34.9325 27.3483 34.4564C26.8697 33.9804 26.4902 33.4151 26.2315 32.793C25.9728 32.1708 25.84 31.504 25.8406 30.8308C25.8406 27.9963 28.1436 25.7054 30.993 25.7054H43.9137C46.7631 25.7054 49.066 27.9963 49.066 30.8308C49.066 33.6652 46.7631 35.9566 43.9133 35.9566H30.993V35.9562Z" fill="white" fill-opacity="0.2"/>
							</g>
							<defs>
								<clipPath id="clip0_43_18">
									<rect width="194" height="49" fill="white"/>
								</clipPath>
							</defs>
						</svg>

						<svg width="194" height="44" viewBox="0 0 194 44" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M112.516 17.1961H104.879V18.0002C107.268 18.0002 107.652 18.5082 107.652 21.5149V26.9352C107.652 29.9415 107.268 30.492 104.879 30.492C103.045 30.2382 101.808 29.2638 100.101 27.4008L98.1386 25.2839C100.783 24.8175 102.191 23.1666 102.191 21.3032C102.191 18.9749 100.187 17.1965 96.432 17.1965H88.9236V18.0002C91.3123 18.0002 91.6965 18.5082 91.6965 21.5149V26.9352C91.6965 29.9415 91.3123 30.492 88.9236 30.492V31.2964H97.413V30.4917C95.0244 30.4917 94.6406 29.9415 94.6406 26.9352V25.411H95.3654L100.101 31.2964H112.516C118.617 31.2964 121.262 28.0788 121.262 24.2249C121.262 20.3717 118.617 17.1961 112.516 17.1961ZM94.6409 24.0977V18.4665H96.3896C98.3091 18.4665 99.1628 19.779 99.1628 21.3036C99.1628 22.7856 98.3091 24.0977 96.3896 24.0977H94.6409ZM112.644 29.984H112.345C110.81 29.984 110.597 29.603 110.597 27.655V18.4665H112.644C117.081 18.4665 117.891 21.6841 117.891 24.1827C117.891 26.7656 117.081 29.984 112.644 29.984ZM65.1617 25.6652L68.1054 17.0265C68.9591 14.5283 68.5748 13.8089 65.8444 13.8089V12.9616H73.8648V13.8089C71.1772 13.8089 70.5376 14.4437 69.471 17.535L64.6069 32.0162H64.0526L59.7005 18.7621L55.2635 32.0162H54.7088L49.974 17.535C48.9501 14.4437 48.2674 13.8089 45.7927 13.8089V12.9616H55.2639V13.8089C52.7468 13.8089 52.0636 14.4016 52.9601 17.0265L55.8182 25.6648L60.1271 12.9616H60.938L65.1617 25.6652ZM79.6662 31.8466C74.9734 31.8466 71.134 28.4169 71.134 24.2245C71.134 20.0753 74.9738 16.6448 79.6662 16.6448C84.3593 16.6448 88.1984 20.0753 88.1984 24.2245C88.1984 28.4169 84.3593 31.8466 79.6662 31.8466ZM79.6662 17.9584C75.7415 17.9584 74.3763 21.4724 74.3763 24.2249C74.3763 27.0202 75.7415 30.492 79.6662 30.492C83.6341 30.492 84.9993 27.0202 84.9993 24.2249C84.9993 21.4724 83.6341 17.9584 79.6662 17.9584Z" fill="white" fill-opacity="0.2"/>
							<path d="M131.799 30.4495V31.2964H122.029V30.4495C124.888 30.4495 125.4 29.7297 125.4 25.4948V18.7207C125.4 14.4854 124.888 13.8085 122.029 13.8085V12.9612H130.86C135.254 12.9612 137.686 15.2056 137.686 18.2123C137.686 21.1343 135.254 23.4204 130.86 23.4204H128.428V25.4944C128.428 29.7297 128.94 30.4495 131.799 30.4495ZM130.86 14.4854H128.428V21.8537H130.86C133.249 21.8537 134.359 20.2024 134.359 18.2123C134.359 16.18 133.249 14.4854 130.86 14.4854ZM166.995 27.3161L166.782 28.0784C166.398 29.4755 165.928 29.9839 162.899 29.9839H162.301C160.084 29.9839 159.699 29.4755 159.699 26.4696V24.5216C163.027 24.5216 163.283 24.8179 163.283 27.0202H164.094V20.7101H163.283C163.283 22.912 163.027 23.2083 159.699 23.2083V18.4661H162.045C165.075 18.4661 165.544 18.9745 165.928 20.3716L166.142 21.1757H166.824L166.526 17.1957H153.982V17.9998C156.371 17.9998 156.756 18.5078 156.756 21.5145V26.9348C156.756 29.685 156.429 30.3777 154.546 30.4766C152.756 30.2051 151.527 29.2359 149.845 27.4004L147.882 25.2835C150.528 24.8171 151.936 23.1662 151.936 21.3028C151.936 18.9745 149.93 17.1961 146.176 17.1961H138.668V17.9998C141.056 17.9998 141.441 18.5078 141.441 21.5145V26.9348C141.441 29.9411 141.057 30.4916 138.668 30.4916V31.296H147.158V30.4913C144.769 30.4913 144.385 29.9411 144.385 26.9348V25.411H145.11L149.845 31.2964H167.379L167.636 27.3165H166.995V27.3161ZM144.384 24.0977V18.4665H146.133C148.053 18.4665 148.907 19.779 148.907 21.3035C148.907 22.7856 148.053 24.0977 146.133 24.0977H144.384ZM175.655 31.8466C173.949 31.8466 172.455 30.9576 171.815 30.4066C171.602 30.6187 171.218 31.2539 171.133 31.8466H170.322V26.0036H171.176C171.517 28.7978 173.479 30.4495 175.997 30.4495C177.362 30.4495 178.471 29.6876 178.471 28.4172C178.471 27.3165 177.49 26.4692 175.741 25.6652L173.309 24.5219C171.602 23.7168 170.322 22.3193 170.322 20.4566C170.322 18.4244 172.242 16.6884 174.887 16.6884C176.296 16.6884 177.489 17.1965 178.215 17.7892C178.428 17.6199 178.642 17.1536 178.77 16.6452H179.581V21.6427H178.685C178.385 19.6522 177.277 18.0009 175.016 18.0009C173.821 18.0009 172.711 18.6786 172.711 19.7376C172.711 20.8383 173.608 21.4306 175.656 22.3625L178.001 23.5058C180.05 24.4794 180.86 26.0469 180.86 27.3169C180.86 29.9843 178.513 31.847 175.655 31.847V31.8466ZM188.795 31.8466C187.088 31.8466 185.595 30.9576 184.955 30.4066C184.742 30.6187 184.358 31.2539 184.273 31.8466H183.463V26.0036H184.315C184.656 28.7978 186.619 30.4495 189.136 30.4495C190.501 30.4495 191.611 29.6876 191.611 28.4172C191.611 27.3165 190.63 26.4692 188.88 25.6652L186.448 24.5219C184.742 23.7168 183.462 22.3193 183.462 20.4566C183.462 18.4244 185.382 16.6884 188.027 16.6884C189.435 16.6884 190.629 17.1965 191.355 17.7892C191.568 17.6199 191.781 17.1536 191.909 16.6452H192.72V21.6427H191.824C191.525 19.6522 190.416 18.0009 188.155 18.0009C186.961 18.0009 185.851 18.6786 185.851 19.7376C185.851 20.8383 186.747 21.4306 188.795 22.3625L191.141 23.5058C193.189 24.4794 193.999 26.0469 193.999 27.3169C193.999 29.9843 191.653 31.847 188.795 31.847V31.8466Z" fill="white" fill-opacity="0.2"/>
							<path d="M3.12825 21.8432C3.12825 29.2608 7.47165 35.6705 13.7695 38.7083L4.76285 14.2169C3.68317 16.6166 3.12615 19.2155 3.12825 21.8436V21.8432ZM34.7548 20.8977C34.7548 18.5819 33.9167 16.978 33.1975 15.7294C32.2404 14.1861 31.3435 12.8788 31.3435 11.3355C31.3435 9.61269 32.6598 8.00913 34.5138 8.00913C34.5975 8.00913 34.6767 8.01966 34.7586 8.02417C31.3996 4.96974 26.9243 3.1052 22.0088 3.1052C15.4128 3.1052 9.60982 6.46386 6.23377 11.5517C6.67709 11.5645 7.09426 11.5739 7.44892 11.5739C9.42378 11.5739 12.4808 11.3358 12.4808 11.3358C13.4985 11.2764 13.6183 12.76 12.602 12.8796C12.602 12.8796 11.579 12.9992 10.4408 13.0582L17.3164 33.3558L21.448 21.0568L18.5065 13.0578C17.4899 12.9984 16.5268 12.8788 16.5268 12.8788C15.509 12.8198 15.6287 11.2757 16.6457 11.3355C16.6457 11.3355 19.7641 11.5731 21.6193 11.5731C23.5934 11.5731 26.6511 11.3355 26.6511 11.3355C27.6692 11.2757 27.789 12.7592 26.772 12.8788C26.772 12.8788 25.7471 12.9984 24.6111 13.0575L31.4341 33.2016L33.3172 26.9551C34.1334 24.3636 34.7548 22.5021 34.7548 20.8977ZM22.3399 23.4825L16.6753 39.82C18.4072 40.3263 20.2033 40.5834 22.0088 40.5834C24.1442 40.5841 26.2643 40.2249 28.2785 39.521C28.2263 39.4391 28.1814 39.3528 28.1444 39.263L22.3399 23.4825ZM38.5757 12.8529C38.6568 13.4497 38.703 14.0902 38.703 14.7799C38.703 16.6813 38.3449 18.8188 37.2669 21.4916L31.5 38.0412C37.1131 34.7923 40.8885 28.7568 40.8885 21.8439C40.8889 18.5857 40.0504 15.5222 38.5757 12.8529ZM22.0088 0C9.87354 0 0 9.79884 0 21.8432C0 33.8894 9.87354 43.6879 22.0088 43.6879C34.144 43.6879 44.0187 33.8894 44.0187 21.8432C44.0187 9.79884 34.144 0 22.0088 0ZM22.0088 42.6864C10.4302 42.6864 1.00903 33.3362 1.00903 21.8432C1.00903 10.3513 10.4298 1.00147 22.0088 1.00147C33.5874 1.00147 43.0078 10.3513 43.0078 21.8432C43.0078 33.3362 33.5874 42.6864 22.0088 42.6864Z" fill="white" fill-opacity="0.2"/>
						</svg>

					</div>
				</div>
			</div>
			<div class="newcomer">
				<div class="newcomer__inner">
					<div class="newcomer__description">
						<h1>Newcomer Tools</h1>
						<h3>Wow! see the latest update of the most <br>recommended tools from reliable designers <br>and developers</h3>
						<a href="#" class="newcomer__link">Explore more</a>
					</div>
					<div class="newcomer__tools">
						<div class="newcomer__block">
							<div class="newcomer__box">
								<div class="newcomer__name">
									<div class="newcomer__item"><<svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
										<g opacity="0.78">
											<path fill-rule="evenodd" clip-rule="evenodd" d="M12.6315 40.3366L9.70191 41.3886L9.54462 49.9551L19.6858 46.3136C16.2075 45.1652 13.6674 43.1445 12.6315 40.3366Z" fill="#FDBD39"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M14.1646 31.2759L4 34.9259L9.70192 41.3885L12.6315 40.3366C11.5986 37.5368 12.2356 34.372 14.1646 31.2759Z" fill="#F69833"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M31.2698 18.9149C18.3262 23.5627 9.98148 33.1535 12.6315 40.3366L59.5047 23.5053C56.8546 16.3222 44.2135 14.267 31.2698 18.9149Z" fill="#FECF33"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M40.8663 44.927C53.8099 40.2791 62.1703 30.7308 59.5046 23.5052L12.6315 40.3365C15.2971 47.5622 27.9226 49.5748 40.8663 44.927Z" fill="#EE6723"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M59.5046 23.5052L12.6315 40.3365C13.5493 42.8244 17.0494 44.0501 21.9604 44.0501C26.7483 44.0501 32.8772 42.886 39.2668 40.5916C52.2106 35.9437 61.3173 28.4186 59.5046 23.5052Z" fill="#F69833"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M50.1756 19.7916C45.3877 19.7916 39.2589 20.9557 32.8692 23.2501C19.9255 27.898 10.8188 35.4231 12.6315 40.3365L59.5046 23.5052C58.5868 21.0173 55.0867 19.7916 50.1756 19.7916Z" fill="#FDBD39"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M47.587 50.4088H47.5867C46.2076 50.4088 44.173 49.1843 41.5394 46.7694C38.4237 43.9124 34.8547 39.7278 31.4896 34.9866C28.1247 30.2455 25.3596 25.5055 23.7039 21.6397C21.9 17.427 21.6428 14.8367 22.9394 13.9408C23.2237 13.7446 23.5665 13.6452 23.958 13.6452C25.0127 13.6452 27.0679 14.4171 30.8682 18.0945L30.9513 18.1749L30.94 18.2892C30.9141 18.5534 30.8901 18.8199 30.8688 19.0816L30.8264 19.6011L30.4536 19.2318C26.3589 15.177 24.5564 14.7392 23.9714 14.7392C23.8046 14.7392 23.6718 14.7726 23.5765 14.8384C23.0141 15.2268 22.9779 17.1294 24.7268 21.2132C26.353 25.0101 29.0778 29.6784 32.3993 34.3581C35.7209 39.0382 39.2354 43.161 42.2954 45.9669C45.5951 48.9925 47.0821 49.3192 47.5683 49.3192C47.7361 49.3192 47.8725 49.2838 47.9737 49.2138C48.567 48.8041 48.5677 46.7659 46.6173 42.3704L46.5278 42.1686L46.7238 42.0631C46.9198 41.9576 47.1094 41.8537 47.2872 41.7544L47.522 41.6232L47.6303 41.867C49.0132 44.9816 50.3059 48.9401 48.6108 50.1114C48.325 50.3087 47.9806 50.4088 47.587 50.4088ZM47.5867 49.9283H47.5871L47.5868 50.1685L47.5867 49.9283Z" fill="#EE6723"/>
											<path fill-rule="evenodd" clip-rule="evenodd" d="M41.1805 44.7959L41.1608 45.0353C40.8335 49.0154 39.9719 53.8003 37.7254 53.994C37.6802 53.998 37.6333 54 37.5865 54C36.0603 54 34.6165 51.8507 33.2951 47.6117C32.0449 43.6013 31.0747 38.2167 30.5634 32.4499C30.052 26.6843 30.0596 21.2154 30.5849 17.0507C31.1575 12.5125 32.2476 10.1424 33.8247 10.0064C33.8713 10.0022 33.9197 10 33.9674 10C35.0745 10 36.7431 11.2322 38.4512 16.9717L37.3359 17.1833C36.7656 15.2653 36.144 13.7054 35.527 12.6335C34.9562 11.642 34.4013 11.096 33.9642 11.096C33.9499 11.096 33.9354 11.0966 33.9212 11.0978C33.2376 11.1568 32.242 12.7867 31.687 17.186C31.171 21.276 31.1648 26.663 31.6695 32.3546C32.1744 38.047 33.1287 43.3511 34.3565 47.2896C34.9064 49.0536 35.5095 50.5073 36.1006 51.4938C36.6458 52.4035 37.1733 52.9045 37.5861 52.9045C37.6003 52.9045 37.6145 52.9038 37.6286 52.9026C38.2826 52.8463 39.5153 51.1502 40.0341 45.1827L41.1805 44.7959Z" fill="#EE6723"/>
										</g>
									</svg>
								</div>
								<div class="newcomer__item"><h2>Zeplin</h2>
									<h3 class="newcomer__price">Free & Paid</h3>
								</div>
							</div>
							<div><p class="newcomer__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
							</div>
							<div class="newcomer__links">
								<div><p class="heard">❤</p></div>
								<div class="newcomer__item"><a href=""><svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
									<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
								</svg>
							</a></div>
							<div class="newcomer__item"><a href="">Visit</a></div>
						</div>
					</div>
					<div class="newcomer__box">
						<div class="newcomer__name">
							<div class="newcomer__item"><svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
								<g clip-path="url(#clip0_50_181)">
									<path d="M36.2057 13.8971L33.1886 4.75429L10.88 0L0 12.3429L34.0114 29.7143L36.2057 13.8971Z" fill="url(#paint0_linear_50_181)"/>
									<path d="M25.6 37.8514L24.96 18.8343L0 12.3429L6.12571 49.0057L25.6 48.8229V37.8514Z" fill="url(#paint1_linear_50_181)"/>
									<path d="M20.2057 37.4858L21.3943 22.4001L39.4971 3.84005L55.68 6.76577L64 27.5201L55.3143 36.1143L41.1428 33.8286L32.3657 43.0629L20.2057 37.4858Z" fill="url(#paint2_linear_50_181)"/>
									<path d="M39.4972 3.84005L13.5315 26.8801L18.5601 56.5029L40.1372 64.0001L64.0001 49.7372L39.4972 3.84005Z" fill="url(#paint3_linear_50_181)"/>
									<path d="M12.2513 12.2514H51.7485V51.7485H12.2513V12.2514Z" fill="black"/>
									<path d="M16 44.3429H30.8114V46.8114H16V44.3429Z" fill="white"/>
									<path d="M15.817 17.3714H22.4913C26.4227 17.3714 28.7999 19.6571 28.7999 23.04V23.1314C28.7999 26.9714 25.8742 28.8914 22.1256 28.8914H19.3827V33.8286H15.817V17.3714ZM22.3084 25.6C24.137 25.6 25.1427 24.5029 25.1427 23.1314V23.04C25.1427 21.3943 24.0456 20.5714 22.217 20.5714H19.4742V25.6H22.3084Z" fill="white"/>
									<path d="M29.7142 31.4514L31.8171 28.8914C33.2799 30.0799 34.8342 30.9028 36.7542 30.9028C38.2171 30.9028 39.1314 30.3542 39.1314 29.3485V29.2571C39.1314 28.3428 38.5828 27.8856 35.8399 27.1542C32.5485 26.3314 30.3542 25.4171 30.3542 22.1256V22.0342C30.3542 19.0171 32.7314 17.0971 36.1142 17.0971C38.4914 17.0971 40.5942 17.8285 42.2399 19.1999L40.3199 21.9428C38.8571 20.9371 37.3942 20.2971 36.0228 20.2971C34.6514 20.2971 33.9199 20.9371 33.9199 21.7599V21.8514C33.9199 22.9485 34.6514 23.3142 37.4857 24.0456C40.7771 24.9599 42.6971 26.1485 42.6971 28.9828V29.0742C42.6971 32.3656 40.2285 34.1942 36.6628 34.1942C34.1942 34.1028 31.7257 33.1885 29.7142 31.4514Z" fill="white"/>
								</g>
								<defs>
									<linearGradient id="paint0_linear_50_181" x1="0.510171" y1="42.8306" x2="27.3801" y2="7.33806" gradientUnits="userSpaceOnUse">
										<stop offset="0.016" stop-color="#765AF8"/>
										<stop offset="0.382" stop-color="#B345F1"/>
										<stop offset="0.758" stop-color="#FA3293"/>
										<stop offset="0.941" stop-color="#FF318C"/>
									</linearGradient>
									<linearGradient id="paint1_linear_50_181" x1="2.496" y1="44.2322" x2="29.323" y2="8.79634" gradientUnits="userSpaceOnUse">
										<stop offset="0.016" stop-color="#765AF8"/>
										<stop offset="0.382" stop-color="#B345F1"/>
										<stop offset="0.758" stop-color="#FA3293"/>
										<stop offset="0.941" stop-color="#FF318C"/>
									</linearGradient>
									<linearGradient id="paint2_linear_50_181" x1="46.4978" y1="42.4275" x2="31.3362" y2="6.44394" gradientUnits="userSpaceOnUse">
										<stop offset="0.183" stop-color="#765AF8"/>
										<stop offset="0.238" stop-color="#8655F6"/>
										<stop offset="0.345" stop-color="#9F4CF3"/>
										<stop offset="0.443" stop-color="#AE47F2"/>
										<stop offset="0.522" stop-color="#B345F1"/>
									</linearGradient>
									<linearGradient id="paint3_linear_50_181" x1="57.8433" y1="52.4243" x2="22.5811" y2="25.1575" gradientUnits="userSpaceOnUse">
										<stop offset="0.016" stop-color="#765AF8"/>
										<stop offset="0.382" stop-color="#B345F1"/>
									</linearGradient>
									<clipPath id="clip0_50_181">
										<rect width="64" height="64" fill="white"/>
									</clipPath>
								</defs>
							</svg>
						</div>
						<div class="newcomer__item"><h2>PHPStorm</h2>
							<h3 class="newcomer__price">Free</h3>
						</div>
					</div>
					<div><p class="newcomer__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
					</div>
					<div class="newcomer__links">
						<div><p class="heard">❤</p></div>
						<div class="newcomer__item"><a href="">
              <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
							<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
						</svg>
					</a></div>
					<div class="newcomer__item"><a href="">Visit</a></div>
				</div>
			</div>
		</div>
		<div class="newcomer__block">
			<div class="newcomer__box">
				<div class="newcomer__name">
					<div class="newcomer__item">
            <svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
						<g opacity="0.78" clip-path="url(#clip0_50_210)">
							<path d="M32 64.152L60 48.13V16.114L32 32.134V64.152Z" fill="#000001"/>
							<path d="M38 49.1112V54L50 46.8888V42L38 49.1112Z" fill="white"/>
							<path d="M32 0.151978L4 16.114V48.13L32 64.152V32.134L60 16.114L32 0.151978Z" fill="url(#paint0_linear_50_210)"/>
						</g>
						<defs>
							<linearGradient id="paint0_linear_50_210" x1="4.36" y1="46.51" x2="60.082" y2="17.564" gradientUnits="userSpaceOnUse">
								<stop offset="0.043" stop-color="#FF8618"/>
								<stop offset="0.382" stop-color="#FF246E"/>
								<stop offset="0.989" stop-color="#AF1DF5"/>
							</linearGradient>
							<clipPath id="clip0_50_210">
								<rect width="64" height="64" fill="white"/>
							</clipPath>
						</defs>
					</svg>
				</div>
				<div class="newcomer__item"><h2>Toolbox</h2>
					<h3 class="newcomer__price">Free</h3>
				</div>
			</div>
			<div><p class="newcomer__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
			</div>
			<div class="newcomer__links">
				<div><p class="heard">❤</p></div>
				<div class="newcomer__item"><a href=""><svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
					<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
				</svg>
			</a></div>
			<div class="newcomer__item"><a href="">Visit</a></div>
		</div>
	</div>
	<div class="newcomer__box">
		<div class="newcomer__name">
			<div class="newcomer__item"><svg width="56" height="56" viewBox="0 0 56 56" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M0 20.2667C0 13.1727 0 9.62567 1.38058 6.91612C2.59498 4.53273 4.53273 2.59498 6.91612 1.38058C9.62567 0 13.1727 0 20.2667 0H35.7333C42.8273 0 46.3743 0 49.0839 1.38058C51.4673 2.59498 53.405 4.53273 54.6194 6.91612C56 9.62567 56 13.1727 56 20.2667V35.7333C56 42.8273 56 46.3743 54.6194 49.0839C53.405 51.4673 51.4673 53.405 49.0839 54.6194C46.3743 56 42.8273 56 35.7333 56H20.2667C13.1727 56 9.62567 56 6.91612 54.6194C4.53273 53.405 2.59498 51.4673 1.38058 49.0839C0 46.3743 0 42.8273 0 35.7333V20.2667Z" fill="#1E252B"/>
				<path d="M15.7334 28.8C7.93342 34.5408 6.40002 42.9334 6.40002 49.9334C6.75558 47.8445 8.38669 42.9467 12.0667 40.0667C17.5334 35.7884 27.5333 37.1978 38.4667 29.9334C49.4001 22.6689 50.4667 13.2 49.0667 5.93335C48.094 12.9451 44.7744 16.001 40.2 18.7334C30.2668 24.6667 24.0668 22.6667 15.7334 28.8Z" fill="url(#paint0_linear_50_199)"/>
				<path d="M15.7334 28.8C7.93342 34.5408 6.40002 42.9334 6.40002 49.9334C6.75558 47.8445 8.38669 42.9467 12.0667 40.0667C17.5334 35.7884 27.5333 37.1978 38.4667 29.9334C49.4001 22.6689 50.4667 13.2 49.0667 5.93335C48.094 12.9451 44.7744 16.001 40.2 18.7334C30.2668 24.6667 24.0668 22.6667 15.7334 28.8Z" fill="url(#paint1_linear_50_199)"/>
				<path d="M6.49329 47.0639C6.9213 40.739 8.97503 33.774 15.7333 28.8C20.0777 25.6025 23.8422 24.6155 27.8582 23.5626C30.2018 22.9482 32.6311 22.3113 35.3112 21.1995C34.3334 22.1333 29.6871 24.3133 26.1825 25.7699C22.6871 27.2227 19.0018 28.7543 15.9334 30.8C9.77698 34.9042 7.27374 42.045 6.49329 47.0639Z" fill="url(#paint2_linear_50_199)"/>
				<path d="M6.49329 47.0639C6.9213 40.739 8.97503 33.774 15.7333 28.8C20.0777 25.6025 23.8422 24.6155 27.8582 23.5626C30.2018 22.9482 32.6311 22.3113 35.3112 21.1995C34.3334 22.1333 29.6871 24.3133 26.1825 25.7699C22.6871 27.2227 19.0018 28.7543 15.9334 30.8C9.77698 34.9042 7.27374 42.045 6.49329 47.0639Z" fill="url(#paint3_linear_50_199)"/>
				<path d="M44.4355 24.7418C43.6689 25.4927 42.8141 26.1649 41.8668 26.7333C37.6001 29.2934 33.065 30.1189 28.6522 30.9223C25.1357 31.5624 21.6969 32.1884 18.5334 33.6667C11.4006 36.9998 7.00069 43.9324 6.40023 49.9322C6.40018 49.9324 6.40014 49.9327 6.4001 49.9329C6.40007 49.9318 6.40005 49.9308 6.40002 49.9297C6.40006 49.4717 6.40666 49.0078 6.42115 48.539C6.4575 47.7953 6.53438 46.9713 6.66161 46.0926C7.60328 41.1584 10.1644 34.646 15.9334 30.8C18.3756 29.1719 21.2084 27.8693 24.0254 26.673C26.5027 25.8597 28.7354 25.3535 30.8626 24.8712C34.2111 24.1121 37.2983 23.4122 40.6668 21.6667C47.7349 18.0041 49.5868 10.4776 49.089 6.05029C50.1458 11.6601 49.7186 18.5598 44.4355 24.7418Z" fill="url(#paint4_linear_50_199)"/>
				<path d="M44.4353 24.7419C43.6687 25.4928 42.814 26.165 41.8667 26.7334C37.6 29.2934 33.0649 30.119 28.6521 30.9223C25.1357 31.5624 21.6968 32.1884 18.5334 33.6667C14.4313 35.5836 11.2331 38.691 9.1416 42.1268C10.987 39.5337 13.7983 36.637 17.2667 35.5334C20.6512 34.4565 23.8795 34.3452 27.2333 34.2296C28.1946 34.1965 29.1662 34.163 30.1547 34.1063C32.8189 33.1365 35.6109 31.8308 38.4666 29.9334C40.9281 28.2979 42.8895 26.5506 44.4353 24.7419Z" fill="url(#paint5_linear_50_199)"/>
				<path d="M44.4353 24.7419C43.6687 25.4928 42.814 26.165 41.8667 26.7334C37.6 29.2934 33.0649 30.119 28.6521 30.9223C25.1357 31.5624 21.6968 32.1884 18.5334 33.6667C14.4313 35.5836 11.2331 38.691 9.1416 42.1268C10.987 39.5337 13.7983 36.637 17.2667 35.5334C20.6512 34.4565 23.8795 34.3452 27.2333 34.2296C28.1946 34.1965 29.1662 34.163 30.1547 34.1063C32.8189 33.1365 35.6109 31.8308 38.4666 29.9334C40.9281 28.2979 42.8895 26.5506 44.4353 24.7419Z" fill="url(#paint6_linear_50_199)"/>
				<path d="M49.0889 6.05029C49.0816 6.01125 49.0741 5.97227 49.0666 5.93335C48.0939 12.9451 44.7744 16.001 40.2 18.7334C38.4671 19.7684 36.8479 20.5621 35.3111 21.1996C34.3331 22.1335 29.687 24.3134 26.1825 25.7699L26.1819 25.7701C25.4687 26.0666 24.7476 26.3663 24.0254 26.673C26.5027 25.8597 28.7353 25.3535 30.8625 24.8712C34.2111 24.1121 37.2982 23.4122 40.6667 21.6667C47.7349 18.0041 49.5867 10.4776 49.0889 6.05029Z" fill="url(#paint7_linear_50_199)"/>
				<path d="M49.0889 6.05029C49.0816 6.01125 49.0741 5.97227 49.0666 5.93335C48.0939 12.9451 44.7744 16.001 40.2 18.7334C38.4671 19.7684 36.8479 20.5621 35.3111 21.1996C34.3331 22.1335 29.687 24.3134 26.1825 25.7699L26.1819 25.7701C25.4687 26.0666 24.7476 26.3663 24.0254 26.673C26.5027 25.8597 28.7353 25.3535 30.8625 24.8712C34.2111 24.1121 37.2982 23.4122 40.6667 21.6667C47.7349 18.0041 49.5867 10.4776 49.0889 6.05029Z" fill="url(#paint8_linear_50_199)"/>
				<defs>
					<linearGradient id="paint0_linear_50_199" x1="30.8" y1="32.4" x2="7.73336" y2="48.9333" gradientUnits="userSpaceOnUse">
						<stop stop-color="#FE5004"/>
						<stop offset="0.602538" stop-color="#FFB915"/>
						<stop offset="1" stop-color="#FFFC41"/>
					</linearGradient>
					<linearGradient id="paint1_linear_50_199" x1="21.6667" y1="33.8" x2="21.8" y2="36.2" gradientUnits="userSpaceOnUse">
						<stop stop-color="#FD3E00"/>
						<stop offset="1" stop-color="#FD4400" stop-opacity="0"/>
					</linearGradient>
					<linearGradient id="paint2_linear_50_199" x1="35.3333" y1="20" x2="2.79999" y2="48.9333" gradientUnits="userSpaceOnUse">
						<stop stop-color="#005FC6"/>
						<stop offset="0.279756" stop-color="#23A4DF"/>
						<stop offset="0.465158" stop-color="#3AC2B7"/>
						<stop offset="0.640642" stop-color="#60EC7A"/>
						<stop offset="0.818668" stop-color="#CFFDBD"/>
						<stop offset="1" stop-color="#D0FCB6"/>
					</linearGradient>
					<linearGradient id="paint3_linear_50_199" x1="28.7333" y1="25.5333" x2="25.9333" y2="23" gradientUnits="userSpaceOnUse">
						<stop stop-color="#0061CB"/>
						<stop offset="1" stop-color="#067EEA" stop-opacity="0"/>
					</linearGradient>
					<linearGradient id="paint4_linear_50_199" x1="49.2" y1="6.00002" x2="6.40003" y2="49.8667" gradientUnits="userSpaceOnUse">
						<stop stop-color="#8E55F1"/>
						<stop offset="0.140795" stop-color="#8B48DF"/>
						<stop offset="0.274905" stop-color="#E04DD9"/>
						<stop offset="0.492309" stop-color="#F496C8"/>
						<stop offset="0.633104" stop-color="#FAD2BA"/>
						<stop offset="0.856964" stop-color="#FEF7E5"/>
						<stop offset="1" stop-color="#FFF5BF"/>
					</linearGradient>
					<linearGradient id="paint5_linear_50_199" x1="44.9999" y1="24.3334" x2="10.0666" y2="40.1334" gradientUnits="userSpaceOnUse">
						<stop stop-color="#F41A73"/>
						<stop offset="0.399909" stop-color="#FC50A3"/>
						<stop offset="0.584511" stop-color="#FE9485"/>
						<stop offset="0.703104" stop-color="#FFAF88"/>
						<stop offset="1" stop-color="#FFC385"/>
					</linearGradient>
					<linearGradient id="paint6_linear_50_199" x1="32.3999" y1="29.2" x2="32.4666" y2="32.4" gradientUnits="userSpaceOnUse">
						<stop stop-color="#9B0008"/>
						<stop offset="1" stop-color="#EA115A" stop-opacity="0"/>
					</linearGradient>
					<linearGradient id="paint7_linear_50_199" x1="49.2" y1="9.60002" x2="17.6666" y2="30.2" gradientUnits="userSpaceOnUse">
						<stop stop-color="#231283"/>
						<stop offset="0.362865" stop-color="#7053C6"/>
						<stop offset="0.466353" stop-color="#7272DB"/>
						<stop offset="0.634311" stop-color="#399EE9"/>
						<stop offset="1" stop-color="#00CFFF"/>
					</linearGradient>
					<linearGradient id="paint8_linear_50_199" x1="41.3333" y1="20" x2="42.7333" y2="21.8" gradientUnits="userSpaceOnUse">
						<stop stop-color="#3F259D" stop-opacity="0"/>
						<stop offset="1" stop-color="#412DAA"/>
					</linearGradient>
				</defs>
			</svg>
		</div>
		<div class="newcomer__item"><h2>Procreate</h2>
			<h3 class="newcomer__price">Paid</h3>
		</div>
	</div>
	<div><p class="newcomer__item">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="newcomer__links">
		<div><p class="heard">❤</p></div>
		<div class="newcomer__item"><a href=""><svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
			<path d="M15.5 12.25H14.25V11C14.25 10.6685 14.1183 10.3505 13.8839 10.1161C13.6495 9.8817 13.3315 9.75 13 9.75C12.6685 9.75 12.3505 9.8817 12.1161 10.1161C11.8817 10.3505 11.75 10.6685 11.75 11V12.25H10.5C10.1685 12.25 9.85054 12.3817 9.61612 12.6161C9.3817 12.8505 9.25 13.1685 9.25 13.5C9.25 13.8315 9.3817 14.1495 9.61612 14.3839C9.85054 14.6183 10.1685 14.75 10.5 14.75H11.75V16C11.75 16.3315 11.8817 16.6495 12.1161 16.8839C12.3505 17.1183 12.6685 17.25 13 17.25C13.3315 17.25 13.6495 17.1183 13.8839 16.8839C14.1183 16.6495 14.25 16.3315 14.25 16V14.75H15.5C15.8315 14.75 16.1495 14.6183 16.3839 14.3839C16.6183 14.1495 16.75 13.8315 16.75 13.5C16.75 13.1685 16.6183 12.8505 16.3839 12.6161C16.1495 12.3817 15.8315 12.25 15.5 12.25Z" fill="white" fill-opacity="0.38"/>
			<path d="M22.375 4.81249H13.625L10.3375 0.837489C10.2212 0.694097 10.0745 0.578254 9.90812 0.498286C9.7417 0.418318 9.55963 0.37621 9.375 0.374989H3.625C2.80826 0.364962 2.02083 0.678982 1.43512 1.24829C0.849416 1.8176 0.513166 2.59579 0.5 3.41249V18.5875C0.513166 19.4042 0.849416 20.1824 1.43512 20.7517C2.02083 21.321 2.80826 21.635 3.625 21.625H22.375C23.1917 21.635 23.9792 21.321 24.5649 20.7517C25.1506 20.1824 25.4868 19.4042 25.5 18.5875V7.84999C25.4868 7.03329 25.1506 6.2551 24.5649 5.68579C23.9792 5.11648 23.1917 4.80246 22.375 4.81249ZM23 18.5625C22.9953 18.6392 22.9753 18.7142 22.9411 18.783C22.9069 18.8518 22.8593 18.9131 22.801 18.9632C22.7427 19.0133 22.675 19.0512 22.6019 19.0747C22.5287 19.0982 22.4515 19.1068 22.375 19.1H3.625C3.54846 19.1068 3.47132 19.0982 3.39815 19.0747C3.32498 19.0512 3.25726 19.0133 3.199 18.9632C3.14073 18.9131 3.0931 18.8518 3.05892 18.783C3.02474 18.7142 3.00471 18.6392 3 18.5625V3.41249C3.00471 3.33578 3.02474 3.2608 3.05892 3.19197C3.0931 3.12315 3.14073 3.06187 3.199 3.01176C3.25726 2.96165 3.32498 2.92373 3.39815 2.90024C3.47132 2.87675 3.54846 2.86816 3.625 2.87499H8.7875L12.0375 6.84999C12.1538 6.99338 12.3005 7.10922 12.4669 7.18919C12.6333 7.26916 12.8154 7.31127 13 7.31249H22.375C22.4515 7.30566 22.5287 7.31425 22.6019 7.33774C22.675 7.36123 22.7427 7.39915 22.801 7.44926C22.8593 7.49937 22.9069 7.56065 22.9411 7.62948C22.9753 7.6983 22.9953 7.77328 23 7.84999V18.5625Z" fill="white" fill-opacity="0.38"/>
		</svg>
	</a></div>
	<div class="newcomer__item"><a href="">Visit</a></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="team">
	<div class="team__inner">
		<div class="team__box">
			<div class="team__picture">
				<a href="https://imgbb.com/"><img class="team__image" src="https://i.ibb.co/94MJKbZ/man.png" alt="man" border="0"></a>
				<div class="team__text">
					<h2>Ronald Richards</h2>
					<p>Product Manager</p>
				</div>
			</div>
			<div class="team__description">
				<p>Incididunt cillum do sint sint enim ullamco id deserunt mollit qui reprehenderit do. Velit ex tempor cillum ad sint occaecat. Do nulla velit labore occaecat do deserunt Lorem magna officia incididunt consectetur amet. Sunt consectetur veniam minim ex commodo sint non. Occaecat aute officia excepteur non laboris id qui ad.</p>
				<svg class="team__quote" width="101" height="97" viewBox="0 0 101 97" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M43.5006 6.57674L48.9333 14.5524C46.4355 16.1545 43.4521 18.6465 39.9828 22.0283C36.671 25.4648 33.4312 29.4557 30.2634 34.001C27.3077 38.4435 25.2453 43.1083 24.076 47.9953C26.2388 47.8648 28.2647 48.1278 30.1538 48.7844C33.6173 49.9882 36.1193 52.1812 37.66 55.3634C39.4128 58.4429 39.6052 61.9505 38.2373 65.8862C36.6505 70.4516 34.0265 73.6861 30.3653 75.5896C26.7588 77.3357 22.909 77.4974 18.8158 76.0748C12.6761 73.9408 8.77067 70.2013 7.09947 64.8564C5.64042 59.4088 6.0326 53.4577 8.27602 47.0031C9.75339 42.7525 12.1854 38.0397 15.5721 32.8648C19.1162 27.7445 23.2901 22.8431 28.0936 18.1606C32.8972 13.4781 38.0328 9.6168 43.5006 6.57674ZM86.9509 21.6788L92.3836 29.6544C89.8858 31.2565 86.9024 33.7485 83.4331 37.1303C80.1213 40.5669 76.8815 44.5578 73.7137 49.103C70.758 53.5456 68.6956 58.2103 67.5263 63.0973C69.6891 62.9668 71.715 63.2299 73.6041 63.8865C77.0676 65.0903 79.5696 67.2832 81.1103 70.4654C82.8631 73.5449 83.0555 77.0525 81.6876 80.9882C80.1008 85.5537 77.4768 88.7881 73.8156 90.6916C70.2091 92.4377 66.3593 92.5994 62.2661 91.1768C56.1264 89.0428 52.221 85.3034 50.5498 79.9584C49.0907 74.5108 49.4829 68.5597 51.7263 62.1051C53.2037 57.8546 55.6357 53.1418 59.0224 47.9668C62.5665 42.8465 66.7404 37.9452 71.5439 33.2626C76.3475 28.5801 81.4831 24.7188 86.9509 21.6788Z" fill="url(#paint0_linear_68_8)"/>
					<defs>
						<linearGradient id="paint0_linear_68_8" x1="66.9416" y1="2.11655" x2="-251.985" y2="320.507" gradientUnits="userSpaceOnUse">
							<stop stop-color="#FCFCFC" stop-opacity="0"/>
							<stop offset="1" stop-color="white" stop-opacity="0.5"/>
						</linearGradient>
					</defs>
				</svg>

			</div>
		</div>
		<div class="team__box">
			<div class="team__picture">
				<a href="https://imgbb.com/"><img class="team__image" src="https://i.ibb.co/Fs79xsn/maan.png" alt="maan" border="0"></a>
				<div class="team__text">
					<h2>Harry Stinkerwils</h2>
					<p>Mentor</p>
				</div>
			</div>
			<div class="team__description">
				<p>Incididunt cillum do sint sint enim ullamco id deserunt mollit qui reprehenderit do. Velit ex tempor cillum ad sint occaecat. Do nulla velit labore occaecat do deserunt Lorem magna officia incididunt consectetur amet. Sunt consectetur veniam minim ex commodo sint non. Occaecat aute officia excepteur non laboris id qui ad.</p>
				<svg class="team__quote" width="101" height="97" viewBox="0 0 101 97" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M43.5006 6.57674L48.9333 14.5524C46.4355 16.1545 43.4521 18.6465 39.9828 22.0283C36.671 25.4648 33.4312 29.4557 30.2634 34.001C27.3077 38.4435 25.2453 43.1083 24.076 47.9953C26.2388 47.8648 28.2647 48.1278 30.1538 48.7844C33.6173 49.9882 36.1193 52.1812 37.66 55.3634C39.4128 58.4429 39.6052 61.9505 38.2373 65.8862C36.6505 70.4516 34.0265 73.6861 30.3653 75.5896C26.7588 77.3357 22.909 77.4974 18.8158 76.0748C12.6761 73.9408 8.77067 70.2013 7.09947 64.8564C5.64042 59.4088 6.0326 53.4577 8.27602 47.0031C9.75339 42.7525 12.1854 38.0397 15.5721 32.8648C19.1162 27.7445 23.2901 22.8431 28.0936 18.1606C32.8972 13.4781 38.0328 9.6168 43.5006 6.57674ZM86.9509 21.6788L92.3836 29.6544C89.8858 31.2565 86.9024 33.7485 83.4331 37.1303C80.1213 40.5669 76.8815 44.5578 73.7137 49.103C70.758 53.5456 68.6956 58.2103 67.5263 63.0973C69.6891 62.9668 71.715 63.2299 73.6041 63.8865C77.0676 65.0903 79.5696 67.2832 81.1103 70.4654C82.8631 73.5449 83.0555 77.0525 81.6876 80.9882C80.1008 85.5537 77.4768 88.7881 73.8156 90.6916C70.2091 92.4377 66.3593 92.5994 62.2661 91.1768C56.1264 89.0428 52.221 85.3034 50.5498 79.9584C49.0907 74.5108 49.4829 68.5597 51.7263 62.1051C53.2037 57.8546 55.6357 53.1418 59.0224 47.9668C62.5665 42.8465 66.7404 37.9452 71.5439 33.2626C76.3475 28.5801 81.4831 24.7188 86.9509 21.6788Z" fill="url(#paint0_linear_68_8)"/>
					<defs>
						<linearGradient id="paint0_linear_68_8" x1="66.9416" y1="2.11655" x2="-251.985" y2="320.507" gradientUnits="userSpaceOnUse">
							<stop stop-color="#FCFCFC" stop-opacity="0"/>
							<stop offset="1" stop-color="white" stop-opacity="0.5"/>
						</linearGradient>
					</defs>
				</svg>
			</div>
		</div>
	</div>
</div>
<div class="contributor">
	<div class="contributor__inner">
		<h1>Become a contributor?</h1> <br>
		<h3>Join us and get tips & tricks to become a great <br> Designer and Developer</h3>
		<div class="contributor__form">
			<input type="text" placeholder="Enter your email">
			<a class="contributor__button" href="">Join us</a>
		</div>
	</div>
</div>
<div class="footer">
	<div class="footer__inner">
		<div class="footer__block">
			<div class="footer__logo">
				<svg class="footer__image" width="38" height="38" viewBox="0 0 38 38" fill="none" xmlns="http://www.w3.org/2000/svg">
					<rect width="38" height="38" rx="8" fill="#FF6E30"/>
					<path fill-rule="evenodd" clip-rule="evenodd" d="M19.9645 12.4359C19.632 12.4359 19.3089 12.4769 19 12.5542C19.1988 10.7606 19.9148 9.12398 20.9963 7.79492C25.2971 8.30464 28.6332 11.9646 28.6332 16.4029V22.7294C28.4605 22.7391 28.2864 22.744 28.1112 22.744C24.6706 22.744 21.6709 20.8483 20.1028 18.0423H23.9315V16.4029C23.9315 14.212 22.1554 12.4359 19.9645 12.4359Z" fill="white"/>
					<path fill-rule="evenodd" clip-rule="evenodd" d="M9.25642 16.9507C9.25642 11.625 13.5738 7.30762 18.8995 7.30762C21.5623 7.30762 23.9731 8.38695 25.7182 10.132C24.1095 8.52336 21.9351 7.48044 19.5191 7.32724C17.894 9.12575 16.9044 11.5095 16.9044 14.1243C16.9044 14.3194 16.9099 14.5131 16.9208 14.7055C16.299 15.2538 15.9068 16.0565 15.9068 16.9507V17.6157H21.8922L17.5214 17.6158C18.9445 21.4968 22.672 24.2661 27.0462 24.2661C27.5546 24.2661 28.0543 24.2287 28.5425 24.1565V28.2563H21.8922V24.2661H15.9068V28.2563H9.25642V20.9409V16.9507Z" fill="white"/>
				</svg>

				
				<h2>antools</h2>
			</div>
			<p>Copyright 2021. Antools</p>
			<p class="footer__text">Antool is a web collection of <br>information on paid or free Design <br> and Development tools</p>
		</div>
		<div class="footer__block">
			<h2>Contact Us</h2>
			<a>+621987463</a>
			<a>M Building, No.10 A</a>
			<a>antools@awesome.com</a>
		</div>
		<div class="footer__block">
			<h2>Categories</h2>
			<a>Design</a>
			<a>Development</a>
		</div>
		<div class="footer__block">
			<h2>Company info</h2>
			<a>About Us</a>
			<a>Our Partners</a>

		</div>
	</div>
</div>

<script>
	let page = document.querySelector('.page');
	let moreButton = document.querySelector('.popular__load');

	moreButton.onclick = function() {
		if (page.classList.contains('page') == true) {
			page.classList.remove('page');
			page.classList.add('popular__block');
		} else {
			page.classList.remove('popular__block');
			page.classList.add('page');
		}
	};

</script>

<script>
	$('.heard').click(function() {
    $(this).toggleClass('active');
    $(this).toggleClass('heard');
});
</script>



<script type="text/javascript">
	$(document).ready(function(){
		$('.team__inner').slick({
			autoplay: false,
			dots: false,
			slidesToShow: 1,
			slidesToScroll: 1,
		});
	});
</script>


</body>
</html>
