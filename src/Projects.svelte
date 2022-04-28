<script>
  
      import Button from "./Button.svelte"



</script>
<section class="projects">

   

    <h2>KEA - COPENHAGEN SCHOOL AND TECHNOLOGY AND DESIGN</h2>
   


<div class="disclmr">
    
    
    <!-- <img class="img1" src="./mood.png" alt=""> -->
   
   
   

    <div class="indhold1">
    <h3>[[ DISCLMR</h3>
    <p>this project created a fundamental understanding of 
        the interaction between the user and the userinterface as 
        well as which theories, tool and metheos to apply for reaseach, 
        design and text in digital content-production. theme 03 revoles around 
        different insights about the users instead of guesses and assumptions</p>
        <Button>click here to watch the process and final product</Button>
    </div>
</div>


<div class="grob">
    
    <!-- <img class="img2" src="./GROB.png" alt=""> -->

   

    <div class="indhold2">
    <h3>[[ TEATER GROB</h3>
    <p>theme 08 mainly focuses on working with content-production in forms of SoMe, 
        video-produktion and graphic elements across different platforms. 
        this theme had a strong focus on planing, ide-generation and concept development. 
        in this theme our client was Teater Grob and our task where to make a campaign-site and content</p>
        <Button>click here to watch the process and final product</Button>
    </div>
</div>

<div class="ungdomsbyen">
    
    <!-- <img class="img3" src="./ungdomsbyen.png" alt=""> -->

   

    <div class="indhold3">
    <h3>[[ Ungdomsbyen</h3>
    <p>theme 09 where centered around information-architecture and dynamic web-solutions. 
        our client where Ungdomsbyen, and the task where to redesign their site and improve 
        the information-architecture</p>
        <Button>click here to watch the original product</Button>
        <Button>click here to watch the process and final product</Button>
    </div>
</div>

<div class="same">
    
    <!-- <img class="img4" src="./same.png" alt=""> -->

   

    <div class="indhold4">
    <h3>[[ SAME</h3>
    <p>this project created a fundamental understanding of 
        the interaction between the user and the userinterface as 
        well as which theories, tool and metheos to apply for reaseach, 
        design and text in digital content-production. theme 03 revoles around 
        different insights about the users instead of guesses and assumptions</p>
        <Button>click here to watch the process and final product</Button>
    </div>
</div>


</section>


<style>



    section {
        background-color:  var(--primary-text-color);
        padding-bottom: 2rem;
        /* padding: 0.5rem; */
    }

    .disclmr, .grob, .ungdomsbyen, .same {
        padding-top: 1rem;
    }

    /* .img1, .img2, .img3, .img4 {
        width: 20rem;
        border: 1px solid white;
        margin-left: 2rem;
    
    } */

   


    p {
        color: var(--secondary-text-color);
        font-family: "futura";
    }

    h2 {
        color: white;
        margin-left: 1.5rem;
        margin-right: 1.5rem;
        padding-top: 2rem;
       
       
    }

   

    h3 {
        color: white;
        font-family: "futura";
        font-weight: lighter;
       
    }

    .indhold1, .indhold2, .indhold3, .indhold4 {
            margin-left: 2rem;
            margin-right: 2rem;
            margin-bottom: 4rem;
        }

    @media (min-width: 800px) {
        /* .img1, .img2, .img3, .img4 {
            display: block;
            width: 20rem;
            border: 1px solid white;
            
        } */

        .disclmr, .grob, .ungdomsbyen, .same {
            display: grid;
            grid-template-columns: 1fr 1fr;
            margin-top: 2rem;
        }

        /* .img1, .img3 {
            grid-column: 1/2;
            margin-top: 3.5rem;
        } */

        .indhold1, .indhold3 {
            grid-column: 2/3;
            margin-left: -4rem;
            margin-right: 2rem;
        }

        /* .img2, .img4 {
            grid-column: 2/3;
            margin-top: 1rem;
        } */

        .indhold2, .indhold4 {
            grid-column: 1/2;
            grid-row: 1;
            margin-top: 0;
            margin-left: 2rem;
            margin-right: -4rem;
        }

            h2 {
                margin-left: 5rem;
            }


        /* .indhold1, .indhold2, .indhold3, .indhold4 {
            margin-left: 4rem;
            margin-right: 3rem;
        } */


       
    }

    @media (min-width: 1250px) {
        .disclmr, .grob, .ungdomsbyen, .same {
            padding-inline: 12rem;
            grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
           
        }

        /* .img1, .img3 {
            grid-column: 2/3;
            margin-top: 1.5rem;
        } */

        .indhold1, .indhold3 {
            grid-column: 3/5;
        }

        /* .img2, .img4 {
            grid-column: 4/5;
            margin-top: 1rem;
        } */

        .indhold2, .indhold4 {
            grid-column: 2/4;
            grid-row: 1;
            margin-top: 0;
        }


    }


    


</style>