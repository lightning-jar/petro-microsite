<script lang="ts">
	import logo_svg from '../assets/renewable-skills-logo-01.svg'
	import logo_png from '../assets/renewable-skills-logo-01.png'
</script>
<header data-lj="simple-header">
	<!-- branding -->
	<div class="brand">
		<picture>
			<source srcset={logo_svg} type="image/svg+xml" />
			<img src={logo_png} draggable="false" alt="Renewable Skills logo" width="240" height="44"/>
		</picture>
	</div>

	<!---nav & button group -->
	<div class="nv-group">

		<!-- Hamburger Nav -->
		<input class="side-menu-control" type="checkbox" id="side-menu-control"/>
		<label class="hamburger" for="side-menu-control">
			<span class="hamburger-line"></span>
		</label>

		<!---Desktop Navbar -->
		<div class="nv-bar">
			<ul>
				<li><a href="/who-we-are">Who We Are</a></li>
				<li><a href="/what-we-do">What We Do</a></li>
				<li><a href="contact-us">Contact Us</a></li>
			</ul>
		</div>
	</div>
</header>

