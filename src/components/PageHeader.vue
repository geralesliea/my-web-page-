<template>
<section id="welcome">
   <div class="skewed-bg">
		<div class="content">
				<header class="close">
					<nav class="nav">
						<div class="container">
							<div class="menu-bg"></div>
							<div class="menu-burger">☰</div>
							<div class="menu-items">
								<div><a href="#welcome">Home</a></div>
								<div><a href="#about">About Me</a></div>
								<div><a href="#portfolio">Skills</a></div>
								<div><a href="#resume">Portfolio</a></div>
								<div><a href="#contactMe">Contact Me</a></div>
							</div>
						</div>
					</nav>
				</header>
				<div class="welcome">
					<i class="logo fade-in one"></i>
					<h1 class="fade-in two">Hello, <strong>World</strong></h1>
					<p class="fade-in three">I am <strong>Geraldine De La Vega</strong>
						A <strong>Front-End</strong>
						<span class="rw-words rw-words-1"><span>tech.</span>
						<span>web development.</span>
						<span>design</span>
						<span>social media.</span>
						<span>gifs.</span>
					</span></p>
					<p><a href="#about" class="button fade-in four">Welcome to me</a></p>
					<div class="scroll-down clear"><i class="fa fa-angle-double-down animated infinite bounce"></i>
					</div>
				</div>
		</div>
	</div>
</section>
</template>
<script>
 
</script>

<style scoped>
@import url('Audrey-Normal.css');

@font-face {
	font-family:'Audrey-Normal';
	src: url('Audrey-Normal_gdi.eot');
	src: url('Audrey-Normal_gdi.eot?#iefix') format('embedded-opentype'),
	url('Audrey-Normal_gdi.woff') format('woff'),
	url('Audrey-Normal_gdi.ttf') format('truetype'),
	url('Audrey-Normal_gdi.otf') format('opentype'),
	url('Audrey-Normal_gdi.svg#Audrey-Normal') format('svg');
	font-weight: 400;
	font-style: normal;
	font-stretch: normal;
	unicode-range: U+0020-25CA;
}
@font-face {
	font-family: "Audrey-Normal";
	src: url("fonts/Audrey-Normal.otf");
}

@import "compass";
@import url(https://reset5.googlecode.com/hg/reset.min.css);

* {
	box-sizing: border-box;
}

html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font: inherit;
	font-size: 100%;
	vertical-align: baseline;
}
.menu, .menu-bg, .menu-burger {
  position: fixed;
  width: 50px;
  height: 50px;
  font-size: 30px;
  text-align: center;
  border-radius: 100%;
  right: 25px;
  top: 25px;
	/*z-index: 1030;*/
	border-width: 0 0 1px;
}

.menu-bg {
	position: fixed;
  background: #f91791;
  pointer-events: none;
  transition: .3s;
  right: 50px;
  top: 50px;
  transform: translate3d(50%, -50%, 0);
  transform-origin: center center;
}
.menu-bg.fs {
  transform: translate3d(50%, -50%, 0);
  width: 2000vw;
  height: 2000vw;
}

.menu-burger {
	position: fixed;
  color: #fff;
  padding-top: 11px;
  user-select: none;
  cursor: pointer;
  transition: .4s;
  transform-origin: center;
}
.menu-burger.fs {
  transform: rotate(-180deg) translateY(10px);
}

.menu-items {
	font-family: 'Abril Fatface', serif;
	font-size: 125px;
	line-height: 120px;
  	position: absolute;
  	color: #fff;
  	width: 100%;
  	text-align: left;
  	opacity: 0;
  	transition: .4s;
  	margin-top: 25px;
  	transform: translateY(-200%);
  	pointer-events: none;
	-webkit-font-smoothing: antialiased;
}

.menu-items div {
	color: #fff;
  	transition: 1s;
  	opacity: 0;
  	margin-top: 0px;
}
.menu-items div a{
	color: #fff;
	text-decoration: none;
}
.menu-items.fs {
  transform: translateY(0);
  pointer-events: auto;
  opacity: 1;
}
.menu-items.fs div {
	color: #fff;
 	opacity: 1;
  /*margin-top: 75px;*/
}
.menu-items.fs div a{
	color: #fff;
	text-decoration: none;
}
.menu-items.fs div a:hover{
	color: #000;
		text-decoration: none;
		transition: .4s;
}
strong {
	color: #f91791
}

.clear-fix {
	clear: both;
}
a:link {
	color: #000
}
a:visited{
	color: #000;
}

</style>




