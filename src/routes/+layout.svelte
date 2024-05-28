<script>
    import "../styles/global.css"
</script>
<div class="container">
    <div class="content">
<main>
    <nav>
        <a href="/">HOME</a> |
        <a href="/TIMELINE">TIMELINE</a> |
        <a href="/CREATIVES">CREATIVES</a> |
        <a href="/WORKSHOPS">WORKSHOPS</a> | 
        <a href="/ABOUT-US">ABOUT US</a> |
        <a href="/CONTACT">CONTACT</a> |
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
</div>
</div>

<style>
      
    a {
        color: var(--IMPACT-white);
        text-decoration: none;
    }

    a:hover {
        color: var(--IMPACT-yellow);
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

  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: url('/path/to/your/background-image.jpg') no-repeat center center fixed;
    background-size: cover;
  }

  .content {
    width: 375px; /* Width of the mobile layout */
    max-width: 100%;
    background: rgb(0, 0, 0); /* Background color of the mobile content */
    /* box-shadow: 0 0 10px rgba(226, 246, 13, 0.829); */
    border-radius: 20px;
  }


</style>