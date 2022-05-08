<script>
  
      import Button from "./Button.svelte"



</script>
<section class="projects">

   

    <h2>KEA - COPENHAGEN SCHOOL AND TECHNOLOGY AND DESIGN</h2>
   


<div class="disclmr">
    
    <a class="link_p" href="http://cecilierichter.dk/kea/08_brugercentreret_design/teater-grob-wp/wordpress/">
    <img class="img1" src="./grob_com.png" alt="">
    </a>
   

    <div class="indhold1">
        <h3>[[ TEATER GROB</h3>
        <p>this project mainly focused on working with content-production in forms of SoMe, 
            video-produktion and graphic elements across different platforms. 
            this theme had a strong focus on planing, ide-generation and concept development. 
            in this theme our client was Teater Grob and our task where to make a campaign-site and content</p>
            <a href="http://cecilierichter.dk/kea/08_brugercentreret_design/teater-grob-wp/wordpress/">click here to watch the process and final product</a>
    </div>
</div>


<div class="grob">
    
    <a class="link_p" href="https://annemunksgaard.dk/kea/02sem/tema09/ungdomsbyen_wp/">
    <img class="img2" src="./ungdom_com.png" alt="">
</a>

    <div class="indhold2">
        <h3>[[ UNGDOMSBYEN</h3>
        <p>this project where centered around information-architecture and dynamic web-solutions. 
            our client where Ungdomsbyen, and the task where to redesign their site and improve 
            the information-architecture</p>
            <a href="https://ungdomsbyen.dk/">click here to watch the original product</a>
            <div>
            <a href="https://annemunksgaard.dk/kea/02sem/tema09/ungdomsbyen_wp/">click here to watch the final product</a>
        </div>
        </div>

    
</div>

<div class="ungdomsbyen">
    
    <a class="link_p" href="https://annemunksgaard.dk/kea/samedist/">
    <img class="img3" src="./same_com.png" alt="">
</a>
   

    <div class="indhold3">
        <h3>[[ SAME</h3>
        <p>this project was mainly about creating our own font. but it was
            also about understanding typographies and learing about how fonts can be sustaineble
            using virable fonts
        </p>
            <a href="https://annemunksgaard.dk/kea/samedist/">click here to watch the process and final product</a>
    </div>
</div>

<div class="same">
    
    <a class="link_p" href="https://stellular-griffin-4a2fdd.netlify.app/?fbclid=IwAR0AkwMs-BD-GH-223xmekhzzUEQBMX6iOdDwNhfA9YbccflH_AsZJ7fPd4">
    <img class="img4" src="./vildskud_com.png" alt="">
    </a>
   

    <div class="indhold4">
        <h3>[[ VILDSKUD FESTIVAL</h3>
        <p>this project was about creating a sustatineble website with 0.5MB in each page.
            we had to create designsystems and focus on userbility as well as creating a visual look
            that reflected the festival
        </p>
            <a href="https://www.vildskud.dk/">click here to watch the original product</a>
            <div>
            <a href="https://stellular-griffin-4a2fdd.netlify.app/?fbclid=IwAR0AkwMs-BD-GH-223xmekhzzUEQBMX6iOdDwNhfA9YbccflH_AsZJ7fPd4">click here to watch the process and final product</a>
        </div>
        </div>
</div>


</section>


<style>

a {
    color: white;
    cursor: pointer;
    
}

a:hover {
    cursor: pointer;
    text-decoration: underline;
}

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

    .link_p:hover {
        transform: scale(1.1);
        cursor: pointer;
    }

    .link_p {
        cursor: pointer;
    }

    img:hover {
        cursor: pointer;
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
            margin-inline: 2rem;
        }

        /* .img1, .img3 {
            grid-column: 1/2;
            margin-top: 3.5rem;
        } */

        .indhold1, .indhold3 {
            grid-column: 2/3;
            
        }

        /* .img2, .img4 {
            grid-column: 2/3;
            margin-top: 1rem;
        } */

        .indhold2, .indhold4 {
            grid-column: 1/2;
            grid-row: 1;
            margin-top: 0;
            
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
            grid-template-columns: 1fr 1fr;
            padding-block: 6rem;
        }

        /* .img1, .img3 {
            grid-column: 2/3;
            margin-top: 1.5rem;
        } */

        .indhold1, .indhold3 {
            grid-column: 2/3;
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