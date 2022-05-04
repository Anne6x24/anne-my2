<script>
import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
		import * as animateScroll from "svelte-scrollto";
</script>



<div class="foot">
<h3 on:click={() => animateScroll.scrollTo({element: '.section_wrapper'})} href="/#/">ANNE MY MUNKSGAARD THAYSEN</h3>
<img src="" alt="">
</div>

<style>
   
   h3 {
       padding-left: 0.5rem;
       cursor: pointer;
   }

    .foot {
        border-top: 1px solid black;
        border-bottom: 1px solid black;
        width: 100%;
    }

   
</style>