<template>
    <!--================ Start Header Area =================-->
	<header class="header_area">
		<div class="main_menu">
			<nav class="navbar navbar-expand-lg navbar-light">
				<div class="container">
					<!-- Brand and toggle get grouped for better mobile display -->
					<router-link class="navbar-brand logo_h" :to="{ name: 'Home'}"><img src="froentend/img/logo.png" alt=""></router-link>
					<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
					 aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
					<!-- Collect the nav links, forms, and other content for toggling -->
					<div class="collapse navbar-collapse offset" id="navbarSupportedContent">
						<ul class="nav navbar-nav menu_nav justify-content-end" id="menu">
								<li class="nav-item">
									<router-link class="nav-link" :to="{ name: 'Home' }">Home</router-link>
								</li>
								<li class="nav-item">
									<router-link class="nav-link" :to="{ name: 'About' }">About</router-link>
								</li>
								<li class="nav-item">
									<router-link class="nav-link" :to="{ name: 'Services' }">Services</router-link>
								</li>
								<li class="nav-item">
									<router-link class="nav-link" :to="{ name: 'Portfolio' }">Portfolio</router-link>
								</li>
								<li class="nav-item">
									<router-link class="nav-link" :to="{ name: 'Blog' }">Blog</router-link>
								</li>
							<li class="nav-item">
								<router-link class="nav-link" :to="{ name: 'Contact' }">Contact</router-link>
							</li>
							<!--<li class="nav-item submenu dropdown">-->
								<!--<a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true"-->
								 <!--aria-expanded="false">Pages</a>-->
								<!--<ul class="dropdown-menu">-->
									<!--<li class="nav-item"><a class="nav-link" href="elements.html">Elements</a></li>-->
									<!--<li class="nav-item"><a class="nav-link" href="portfolio-details.html">Portfolio Details</a></li>-->
								<!--</ul>-->
							<!--</li>-->
							<!--<li class="nav-item submenu dropdown">-->
								<!--<a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true"-->
								 <!--aria-expanded="false">Blog</a>-->
								<!--<ul class="dropdown-menu">-->
									<!--<li class="nav-item"><a class="nav-link" href="blog.html">Blog</a></li>-->
									<!--<li class="nav-item"><a class="nav-link" href="single-blog.html">Blog Details</a></li>-->
								<!--</ul>-->
							<!--</li>-->
							<!--<li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>-->
						</ul>
					</div>
				</div>
			</nav>
		</div>
	</header>
	<!--================ End Header Area =================-->
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style>
	#menu .router-link-exact-active{
		color: #4458dc;
	}
</style>