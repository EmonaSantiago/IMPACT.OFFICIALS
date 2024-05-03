<body>
    <section id="hero-section">
        <h1>IMPACT</h1>
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

    <section id="form">
        <h2>FEEDBACK</h2>
        <p>Jouw IMPACT telt! Vertel ons hoe het was. Jouw feedback maakt het verschil. Vul ons formulier in en laat ons samen groeien!</p>
        <form
        action="https://formspree.io/f/mwkgynen"
        method="POST"
        >
        <label>
            EMAIL
            <input type="text" name="name" id="full-name" placeholder="ex: myname@example.com" >
        </label>
        <label>
            HOE HEB JIJ IMPACT ERVAREN?
            <input type="text" name="name" id="full-name" placeholder="type hier..." >
        </label>
        <label>
            WAT VOND JE HET MEEST WAARDEVOL AAN JE ERVARING BIJ IMPACT?
            <input type="text" name="name" id="full-name" placeholder="type hier..." >
        </label>
        <label>
            HEB JE NOG ANDERE OPMERKINGEN, SUGGESTIES OF FEEDBACK DIE JE MET ONS WILT DELEN? 
            <input type="text" name="name" id="full-name" placeholder="type hier..." >
        </label>
        
        <!-- your other form fields go here -->
        <a href="/" type="submit" class="button">SEND</a>
        </form>

        <img id="team" src="src/static/team.png" alt="Save the date post">
    </section>
</body>


<style>

    h1 {
        position: static;
        font-size: 100px;
        padding-top: 80px;
        padding-left: 20px;
    }
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

    #form {
        margin: 1em;
        height: 100vh;
        color: white;
    }

    img#instagram-live{
    width: 100%;
    border: solid 1px var(--IMPACT-yellow);
    }

    input[type=text]{
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 3px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    background-color: black;
    }

    ::placeholder {
        color: grey;
    }

    input[type=submit] {
    width: 100%;
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    }

    input[type=submit]:hover {
    background-color: #45a049;
    }

    div {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
    }

    img#team {
        width: 100%;
        margin-top: 2em;
        border-radius: 2em;
    }

</style>