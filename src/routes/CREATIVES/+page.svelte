
<body>
    <h1>CREATIVES PAGINA</h1>
    <div class="section">
      <h2>Designers</h2>
      <div class="carousel">
        <div class="item">
          <img src="src/static/team.png" alt="Designer 1">
          <div class="info">
            <h3>Designer 1</h3>
            <p>An introduction to Designer 1</p>
            <a href="designer1.html" class="btn">View More</a>
          </div>
        </div>
        <div class="item">
          <img src="designer1.jpg" alt="Designer 1">
          <div class="info">
            <h3>Designer 1</h3>
            <p>An introduction to Designer 1</p>
            <a href="designer1.html" class="btn">View More</a>
          </div>
        </div>
        <div class="item">
          <img src="designer1.jpg" alt="Designer 1">
          <div class="info">
            <h3>Designer 1</h3>
            <p>An introduction to Designer 1</p>
            <a href="designer1.html" class="btn">View More</a>
          </div>
        </div>
        <!-- More items here -->
      </div>
    </div>
  
    <div class="section">
      <h2>Photographers</h2>
      <div class="carousel">
        <div class="item">
          <img src="photographer1.jpg" alt="Photographer 1">
          <div class="info">
            <h3>Photographer 1</h3>
            <p>An introduction to Photographer 1</p>
            <a href="photographer1.html" class="btn">View More</a>
          </div>
        </div>
        <!-- More items here -->
      </div>
    </div>

    <div class="section">
        <h2>Photographers</h2>
        <div class="carousel">
          <div class="item">
            <img src="photographer1.jpg" alt="Photographer 1">
            <div class="info">
              <h3>Photographer 1</h3>
              <p>An introduction to Photographer 1</p>
              <a href="photographer1.html" class="btn">View More</a>
            </div>
          </div>
          <!-- More items here -->
        </div>
      </div>
      <div class="section">
        <h2>Photographers</h2>
        <div class="carousel">
          <div class="item">
            <img src="photographer1.jpg" alt="Photographer 1">
            <div class="info">
              <h3>Photographer 1</h3>
              <p>An introduction to Photographer 1</p>
              <a href="photographer1.html" class="btn">View More</a>
            </div>
          </div>
          <!-- More items here -->
        </div>
      </div>
      <div class="section">
        <h2>Photographers</h2>
        <div class="carousel">
          <div class="item">
            <img src="photographer1.jpg" alt="Photographer 1">
            <div class="info">
              <h3>Photographer 1</h3>
              <p>An introduction to Photographer 1</p>
              <a href="photographer1.html" class="btn">View More</a>
            </div>
          </div>
          <!-- More items here -->
        </div>
      </div>
  
    <!-- More sections here -->
  
  </body>

<style>
    /* h1 {
        color: white;
    } */
    body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
}

.section {
  margin-bottom: 30px;
}

h2 {
  margin-bottom: 10px;
  color: white;
}

.carousel {
  display: flex;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
}

.item {
  flex: 0 0 auto;
  width: 300px;
  margin-right: 20px;
  scroll-snap-align: start;
}

.item img {
  width: 100%;
  height: auto;
}

.info {
  padding: 10px;
  background-color: #f2f2f2;
}

.info h3 {
  margin-top: 0;
}

.btn {
  display: block;
  margin-top: 10px;
  padding: 5px 10px;
  text-decoration: none;
  color: #fff;
  background-color: #007bff;
  border: none;
  border-radius: 3px;
}

.btn:hover {
  background-color: #0056b3;
}
</style>