<body>
    <header>
        <h1>ABOUT US</h1>
        <nav>
            <ul>
                <li><a href="#section1">Section 1</a></li>
                <li><a href="#section2">Section 2</a></li>
                <li><a href="#section3">Section 3</a></li>
                <li><a href="#section4">Section 4</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="section1">
            <div class="content">
                <h2>Section 1</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi.</p>
            </div>
        </section>

        <section id="section2">
            <div class="content">
                <h2>Section 2</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi.</p>
            </div>
        </section>

        <section id="section3">
            <div class="content">
                <h2>Section 3</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi.</p>
            </div>
        </section>

        <section id="section4">
            <div class="content">
                <h2>Section 4</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi.</p>
            </div>
        </section>
    </main>
</body>

<style>
    * {
  scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;

}

/* header {
    background-color: #f2f2f2;
    padding: 20px;
    text-align: center;
} */

header {
    margin: 1em;
}

h1 {
    font-size: 36px;
    color: var(--IMPACT-yellow);
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

.content {
 
    padding: 20px;
}

@media screen and (min-width: 768px) {
    main {
        display: flex;
        flex-direction: row-reverse;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    section {
        width: 45%;
    }

    section:nth-child(even) {
        margin-right: 0;
    }

    section:nth-child(odd) {
        margin-left: 0;
    }
}
</style>