<template>
  <header>
	  <div class="container">
		<div class="mainmenu">
            <img :src="require(`~/assets/resources/Panday-digital-long2.png`)" alt="" width="10%">
			<nav class="float">
				<nuxt-link to="/"> <h1 class="font-weight-regular text-xl-h2 text-lg-h3 text-md-h5 text-sm-h2"> HOME </h1></nuxt-link>
				<nuxt-link to="about"> <h1 class="font-weight-regular text-xl-h1 text-lg-h1 text-md-h5 text-sm-h2"> ABOUT </h1></nuxt-link>
				<nuxt-link to="article"> <h1 class="font-weight-light text-xl-h1 text-lg-h1 text-md-h5 text-sm-h2"> ARTICLE </h1></nuxt-link>
			</nav>
		</div>
	  </div>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

  $color-pack: false;

  @import '~vuetify/src/styles/main.sass';
p{
    font-weight: 300;
}
.custom-width {
    height: 65px;
}
h1,
h2,
h3,
h4,
h5,
h6,
p,
li,
a{
    font-family: 'Roboto', sans-serif;
}
nav.float {
    text-transform: uppercase;
}
.first-section h3, .first-section h1, .first-section p {
    color: white;
}
.mainmenu {
    display: flex;
    width: 100%;
    justify-content: space-between;
}
nav {
	display: flex;
	align-items: center;
	margin: 0 -15px;
}
nav a {
	display: block;
	margin: 0 15px;
	color: #9f25cf;
}
.float-left{
	float: right !important;
}
header {
    width: 100%;
    height: 100px;
    display: flex;
    box-shadow: 10px 0px 19px #272626;
    border-radius: 0px 14px 0px 14px;
    z-index: 9;
    position: fixed;
    background-color: white;
}
.title {
    font-weight: 900;
    font-size: 34px;
}
.radius {
    display: flex;
    align-items: center;
}
.Rounded-botton span {
    margin: 0px !important;
}
.first-section {
    position: relative;
    bottom: -20px;
}
.first-section h3 {
    font-weight: 300;
}
.first-section h1 {
    font-size: 38px;
}
.d-flex{
    align-items: center !important;
}
</style>