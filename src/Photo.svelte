<script>
	
    import Button from "./Button.svelte"
  

       
</script>

<section>
 


    <h2>PHOTOGRAFY/GRAFICS</h2>






  
  

    <div class="agency">
        <h4>[[AGENCY6.</h4>
    </div>
    
    
        
     <div class="tutu">
        <h4>[[lilleTUTU</h4>

        <div class="t1">
        <img src="./01tutu.jpg" alt="">
        </div>

        <div class="t2">
            <img src="./02tutu.jpg" alt="">
            </div>

            <div class="t3">
                <img src="./03tutu.jpg" alt="">
                </div>

                <div class="t4">
                    <img src="./04tutu.jpg" alt="">
                    </div>
    </div>
    
    <div class="portraits">
        <h4>[[PORTRAITS</h4>

        <div class="p1">
            <img src="./p1.jpg" alt="">
            </div>
    
            <div class="p2">
                <img src="./p2.jpg" alt="">
                </div>
    
                <div class="p3">
                    <img src="./p3.jpg" alt="">
                    </div>
    
                    <div class="p4">
                        <img src="./p4.jpg" alt="">
                        </div>

                        <div class="p5">
                            <img src="./p5.JPG" alt="">
                            </div>
    </div>
    
    <div class="grafics">
        <h4>[[GRAFICS AND EDITS</h4>
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
            margin-left: 2rem;
            margin-right: 2rem;
            margin-bottom: 4rem;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr;
            gap: 1rem;
    }

    .t1, .t4 {
        grid-column: 1/5;
    }

    .t2 {
        grid-column: 1/3;
        
    }

    .t3 {
        grid-column: 3/5;
    }

    .p1, .p3 {
        grid-column: 1/3;

    }

    .p2, .p4 {
        grid-column: 3/5;
        
    }

    .p5 {
        grid-column: 1/5;
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
        .tutu, .portraits, .agency, .grafics {
            margin-left: 10rem;
            margin-right: 10rem;
            margin-bottom: 4rem;
            
    }
    }

    @media (min-width: 1250px) {
        .tutu, .portraits, .agency, .grafics {
            padding-inline: 12rem;
            
    }
    }




</style>