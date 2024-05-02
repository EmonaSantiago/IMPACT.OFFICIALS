<body>
    <section id="hero-section">
    <!-- <img src="src/static/logo.png" alt="logo/impact"> -->
</section>
<section id="upcoming">
    <h2>UPCOMING</h2>
    <p>ATTENTION IMPACT : WE’RE BACK ⚠️  </p>

    <p>EXCITED TO ANNOUNCE THAT WE’RE ORGANIZING THE 3RD EDITION OF OUR FASHION SHOW AND EXPO EVENT!</p>
    <p>JUNE 1, 2024. MARK IT IN YOUR CALENDAR 📌</p>
    <p>and for all the interested creatives , models or future crew-members out there, be ready for the next post.. 🏃🏻</p>
    <a href="/" class="button">GET TICKETS</a>
    <img id="save-the-date" src="src/static/save-the-date.png" alt="Save the date post">
</section>
<section id="instagram">
    <img id="instagram-live" src="src/static/instagram.png" alt="instagram live feed">
</section>
</body>


<style>
    h2 {
        color: white;
        font-size: 80px;
    }

    a {
        color: white;
    }

    p {
        color: white;
        padding-bottom: 1em;
        font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    }
    body {
        height: 100%;
    }

    #hero-section {
        background-image: url("/src/static/aftermovie.png");
        /* Full height */
        height: 80vh; 

        /* Center and scale the image nicely */
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
    
    #upcoming {
        margin: 1em;
        height: 100vh;
    }

    .button {
        border: solid 3px var(--IMPACT-yellow);
        border-radius: 5px;
        border-color: var(--IMPACT-yellow);
        padding: 10px 50px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
    }

    img#save-the-date {
        width: auto;
        height: 24em;
        margin-top: 2em;
        border-radius: 2em;
    }

    #instagram {
        height: 100vh;
        margin: 1em;
    }

    img#instagram-live{
    width: 100%;
    border: solid 1px var(--IMPACT-yellow);
    }

</style>