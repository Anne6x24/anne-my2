<script>
		import Header from "./Header.svelte"
		import About from "./About.svelte"
		import Projects from "./Projects.svelte"
		import Photo from "./Photo.svelte"
		import Contact from "./Contact.svelte"
		import Footer from "./Footer.svelte"
		import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
		import * as animateScroll from "svelte-scrollto";

	


</script>




<main>


	<Header></Header>



<ul>
	<li><a on:click={() => animateScroll.scrollTo({element: '.about'})} href="/#/">[[ ABOUT</a></li>
	<li><a on:click={() => animateScroll.scrollTo({element: '.bottom'})} href="/#/">[[ KEA-PROJECTS</a></li>
	<li><a on:click={() => animateScroll.scrollTo({element: '.photo'})} href="/#/">[[ PHOTOGRAFY/GRAFICS</a></li>
	<li><a on:click={() => animateScroll.scrollTo({element: '.contact'})} href="/#/">[[ CONTACT</a></li>
	</ul>




	<About></About>




	<Projects></Projects>

	



	<Photo></Photo>



	<Contact></Contact>





</main>

<Footer></Footer>


<style>




	ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		overflow: hidden;
		background-color: white;
		position: -webkit-sticky; /* Safari */
		position: sticky;
		top: 0;
		border-bottom: 1px solid black;

}

li {
float: left;
cursor: pointer;
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
