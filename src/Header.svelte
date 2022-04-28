<script>

  import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling';
  import * as animateScroll from "svelte-scrollto";

import { tick } from 'svelte';


let paused = true;
let time;

function mouseOver (){
    paused = false;
}

async function mouseOut(){

await tick()

time=0;
paused=true;


}



</script>

<section class="section_wrapper">
<video muted loop id="myVideo"
       src="./glitch.mp4"
       bind:paused={paused}
       bind:currentTime={time}
       >
</video>


<h1 on:focus on:pointerenter={mouseOver} on:blur on:pointerleave={mouseOut} id="myBtn" class="heading">ANNE MY MUNKSGAARD THAYSEN</h1>

<div class="pil">
    <a on:click={() => animateScroll.scrollTo({element: '.menu'})} href="/#/"><img src="./down-arrow.png" alt="pil"></a>
</div>



</section>

<style>

.section_wrapper {
    display: grid;
    
}

#myVideo, .heading, .pil {
    grid-area: 1/1;
    
}

.heading {
    /* margin-left: 2rem; */
    font-size: medium;
}

#myVideo {
   height: 844px;
   width: 390px;
   object-fit: cover;
    object-position: center center;
    z-index: -1;
   
}

.pil {
    place-self: end center;
    margin-left: 1rem;
    
}

img {
    width: 15%;
    padding-left: 10rem;
}


.heading {
    place-self: center center;
    color: white;
}



#myBtn:hover {
    /* color: var(--primary-hover-color); */
    color:var(--primary-hover-color);
}


/* mediaquerys */

@media (min-width: 640px) {

    #myVideo {
   /* height: 1080px; */
    width: 640px;
    height: 26.75rem;
    height: clamp(26.75rem, 16.287921348314605rem + 42.921348314606746vw, 50.625rem);
   
}

    .pil {
        margin-left: 8rem;

}



}

@media (min-width: 768px){

    #myVideo {
   /* height: 1080px; */
   width: 810px;
   
}
.pil {
    margin-left: 13rem;
    
}

}



@media (min-width: 1024px) {
    .heading {
        font-size: xx-large;
    }

    .pil {
    margin-left: 15rem;
    
}

img {
    width: 20%;
    padding-left: none;
}


#myVideo {
    width: 100%;
    /* height: auto; */
}

}








</style>


