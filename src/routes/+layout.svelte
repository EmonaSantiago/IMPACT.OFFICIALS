<script>
    import "../styles/global.css"
</script>
<main>
    <nav>
        <a href="/">HOME</a> |
        <a href="/TIMELINE">TIMELINE</a> |
        <a href="/CREATIVES">CREATIVES</a> |
        <a href="/ABOUT-US">ABOUT US</a> |
        <a href="/CONTACT">CONTACT</a> 
    </nav>
<slot/>
<div class="footer">
    <h3>CONTACTGEGEVENS</h3>
    <p>+31 6 22428876</p>
    <p>info.impactofficials@gmail.com</p>
    <h3 id="h3">VOLG ONS OP SOCIAL MEDIA</h3>
    <p>INSTAGRAM</p>
    <p>TIKTOK</p>
<br>
    <p>© 2024 IMPACT</p>
  </div>
</main>

<style>
    a {
        color: var(--IMPACT-white);
        text-decoration: none;
    }

    p {
        margin-top: 4px;
        color: var(--IMPACT-white);
        font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    }

    #h3 {
        margin-top: 2em;
    }

    main {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    }
    nav {
        margin: 1em;
        position: fixed;
    }

    .footer {
        bottom: 0;
        margin: 1em;
        color: white;
        margin-top: auto;
    }

</style>