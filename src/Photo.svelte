<script>
	
    import Button from "./Button.svelte"
  

       
</script>

<section class="photo">
 


    <h2>PHOTOGRAFY/GRAFICS</h2>
  

    <div class="agency">
        <h4>[[ AGENCY6.</h4>

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
    
    
        
     <div class="tutu">
        <h4>[[ lilleTUTU</h4>

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
    
    <div class="portraits">
        <h4>[[ PORTRAITS</h4>

        <div class="p1">
            <img src="./p1.JPG" alt="">
        </div>

        <div class="p2">
            <img src="./p2.jpg" alt="">
        </div>

        <div class="p3">
            <img src="./p3.JPG" alt="">
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
    
    <div class="grafics">
        <h4>[[ GRAFICS AND EDITS</h4>
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

    .tutu, .portraits, .agency, .grafics {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr;
            
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





    h2 {
        color: var(--primary-text-color);
        border-bottom: 1px solid white;
        width: 100%;
        
    }


    h4 {
        color: var(--primary-text-color);
    }


    @media (min-width: 800px) {
     
       h2 {
           margin-top: 5rem;
       } 

    h2, h4 {
                margin-left: 5rem;
            }
    

    .a1:hover, .a2:hover, .a3:hover, .a4:hover, .a5:hover, .a6:hover, .a7:hover, .a8:hover, 
    .t1:hover, .t2:hover, .t3:hover, .t4:hover, .t5:hover, .t6:hover, .t7:hover, .t8:hover,
    .p1:hover, .p2:hover, .p3:hover, .p4:hover, .p5:hover, .p6:hover, .p7:hover, .p8:hover{
        transform: scale(2);
        
    }

    .agency, .tutu, .portraits {
        padding-bottom: 10rem;
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
   

   
    }


</style>