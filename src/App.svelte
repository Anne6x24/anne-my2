<script>
		import Header from "./Header.svelte"
		import Menu from "./Menu.svelte"
		import About from "./About.svelte"
		import Projects from "./Projects.svelte"
		import Photo from "./Photo.svelte"
		import Contact from "./Contact.svelte"
		import Footer from "./Footer.svelte"


</script>




<main>


	<Header></Header>



<ul>
	<li><a href="About.svelte">[[ABOUT</a></li>
	<li><a href="Projects.svelte">[[KEA-PROJECTS</a></li>
	<li><a href="Photo.svelte">[[PHOTOGRAFY/GRAFICS</a></li>
	<li><a href="Contact.svelte">[[CONTACT</a></li>
	</ul>

<section>
	<About></About>
</section>


<section>
	<Projects></Projects>
</section>

	<section>
	<Photo></Photo>
</section>

<section>
	<Contact></Contact>
</section>



</main>

<Footer></Footer>


<style>
	section {
		display: block;
	}



	ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		overflow: hidden;
		background-color: white;
		position: -webkit-sticky; /* Safari */
		position: sticky;
		top: 0;
		border-top: 1px solid black;
		border-bottom: 1px solid black;

}

li {
float: left;
}

li a {
display: block;
color: var(--primary-text-color);
text-align: center;
padding: 14px 16px;
text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
color: var(--primary-hover-color);
}

@media (min-width: 1024px) {
	ul {
		display: flex;
		justify-content: center;
	}

	li a {
		padding: 2rem;
	}
}
</style>
