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
    
    <!-- BODY -->
    <h1>IMPACT APPLICATIE INCOMING . . .</h1>
    
<slot/>
</main>

<style>
    a {
        color: var(--IMPACT-yellow);
        text-decoration: none;
    }

    h1 {
        color: var(--IMPACT-white);
    }
</style>