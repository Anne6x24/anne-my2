<script>
	
    import Button from "./Button.svelte"
  

       
</script>

<section class="photo">
 

<div class="photo_top">
    <h2>PHOTOGRAFY/GRAFICS</h2>
    <h3>below is different photografys taken by me, for more check out my instagram: <a class="font" href="https://www.instagram.com/annemy.jpg/">@annemy.jpg</a></h3>
</div>
  
<div class="top_a">
    <h4><strong>[[ AGENCY6.</strong></h4>
    <p>"AGENCY6 CREATES CREATIVE CONCEPTS AND CAMPAIGNS FOR BRANDS WITHIN THE REALMS OF FASHION, 
        LIFESTYLE, AND ENTERTAINMENT.  DELIVERING ORIGINAL IMAGERY, WITH THE PURPOSE TO MAKE YOUR 
        BRAND STAND OUT." - <i><a href="https://www.agency6.dk/">www.agency6.dk</a></i> </p>
    <p><i>the job here was to capture the launching of the merch t-shirts</i></p>

    </div>
    <div class="agency">

        <div class="a1">
            <img src="./a1.jpg" alt="">
        </div>

        <div class="a2">
            <img src="./a2.jpg" alt="">
        </div>

        <div class="a3">
            <img src="./a3.jpg" alt="">
        </div>

        <div class="a4">
            <img src="./a4.jpg" alt="">
        </div>

        <div class="a5">
            <img src="./a5.jpg" alt="">
        </div>

        <div class="a6">
            <img src="./a6.jpg" alt="">
        </div>

        <div class="a7">
            <img src="./a7.jpg" alt="">
        </div>

        <div class="a8">
            <img src="./a8.jpg" alt="">
        </div>


    </div>
    
    
    <div class="top_a">
        <h4><strong>[[ LILLETUTU</strong></h4>
        <p>LILLE TUTU IS A LOT MORE THAN JUST A SECONDHAND. THEY CREATE THEIR OWN CHLOTING BY UPCYCLING 
            USED CHLOTHES WHILE HELPING FAMILIES CLEANING OUR THEIR KIDS CLOSETS. - <i><a href="https://annemunksgaard.dk/kea/02sem/lilletutu/tutulille_wp/">www.lilletutu_secondhand.dk</a></i> </p>
        <p><i>the job here was to capture the styles in a fall/fun envirement</i></p>
    
        </div>
     <div class="tutu">
        

        <div class="t1">
            <img src="./t1.jpg" alt="">
        </div>

        <div class="t2">
            <img src="./t2.jpg" alt="">
        </div>

        <div class="t3">
            <img src="./t3.jpg" alt="">
        </div>

        <div class="t4">
            <img src="./t4.jpg" alt="">
        </div>

        <div class="t5">
            <img src="./t5.jpg" alt="">
        </div>

        <div class="t6">
            <img src="./t6.jpg" alt="">
        </div>

        <div class="t7">
            <img src="./t7.jpg" alt="">
        </div>

        <div class="t8">
            <img src="./t8.jpg" alt="">
        </div>
    </div>
    
    <div class="top_a">
        <h4><strong>[[ PORTRAITS</strong></h4>
        <p>"ALL PICTURES ARE PHOTOS OF PEOPLE I ADORE. IT IS A PORTRAITS AS WELL
            AS A COLLECTION OF MY SURROUNDINGS AND WHAT MY EYES CAPUTURE IN MY SPARETIME." - <i><a href="https://www.instagram.com/annemy.jpg/">@annemy.jpg</a></i> </p>
        <p><i>this is not a job</i></p>
    
        </div>
    <div class="portraits">
        

        <div class="p1">
            <img src="./p1.png" alt="">
        </div>

        <div class="p2">
            <img src="./p2.jpg" alt="">
        </div>

        <div class="p3">
            <img src="./p3.png" alt="">
        </div>

        <div class="p4">
            <img src="./p4.jpg" alt="">
        </div>

        <div class="p5">
            <img src="./p5.jpg" alt="">
        </div>

        <div class="p6">
            <img src="./p6.jpg" alt="">
        </div>

        <div class="p7">
            <img src="./p7.JPG" alt="">
        </div>

        <div class="p8">
            <img src="./p8.jpg" alt="">
        </div>
    </div>
    
    

</section>


<style>

    section {
        background-color:  none;
    }

    img {
        display: block;
        width: 100%;
        
    }

    .tutu, .portraits, .agency {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr;
            margin-bottom: 5rem;
           
    }


    .a1, .a3, .a5, .a7, 
    .t1, .t3, .t5, .t7,
    .p1, .p3, .p5, .p7 {
        grid-column: 1/3;
        
    }

    .a2, .a4, .a6, .a8, 
    .t2, .t4, .t6, .t8,
    .p2, .p4, .p6, .p8 {
        grid-column: 3/5;
        
    }





    .photo_top {
        color: var(--primary-text-color);
        border-bottom: 1px solid white;
        margin-left: 1.5rem;
        margin-right: 1.5rem;
        padding-top: 2rem;
        
    }

    .top_a {
        margin-left: 1.5rem;
        margin-right: 1.5rem;
    }


    h4 {
        color: var(--primary-text-color);
        
    }


    @media (min-width: 800px) {
     
       h2 {
           margin-top: 5rem;
       } 

    .photo {
                margin-inline: 5rem;
            }

    .top_a {
        margin-inline: 1.5rem;
        margin-bottom: 2rem;
    }
    

    .a1:hover, .a2:hover, .a3:hover, .a4:hover, .a5:hover, .a6:hover, .a7:hover, .a8:hover, 
    .t1:hover, .t2:hover, .t3:hover, .t4:hover, .t5:hover, .t6:hover, .t7:hover, .t8:hover,
    .p1:hover, .p2:hover, .p3:hover, .p4:hover{
        transform: scale(2);
        
    }

    
    .p5:hover, .p6:hover, .p7:hover, .p8:hover{
        transform: scale(1.3);
        
    }

    .agency, .tutu, .portraits {
        padding-bottom: 4rem;
    }

    .a1, .a5, 
    .t1, .t5,
    .p1, .p5 {
        grid-column: 1/2;
        
    }

    .a2, .a6, 
    .t2, .t6,
    .p2, .p6 {
        grid-column: 2/3;
        
    }

    .a3, .a7, 
    .t3, .t7,
    .p3, .p7 {
        grid-column: 3/4;
        
    }

    .a4, .a8, 
    .t4, .t8,
    .p4, .p8 {
        grid-column: 4/5;
        
    }
   p {
       max-width: 75ch;
   }

   
    }

    @media (min-width: 1250px) {
        .agency, .tutu, .portraits {
        padding-bottom: 10rem;
    }
    }



</style>