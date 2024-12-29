<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    

    <!-- bootstrap css cdn link  -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65"
      crossorigin="anonymous"
    />

    <!-- custom css file -->
    <link rel="stylesheet" href="css/style.css" />

    <!-- google font link -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&display=swap"
      rel="stylesheet"
    />

    <!-- bootstrap icon cdn link  -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.4/font/bootstrap-icons.css"
    />

    <!-- for adding animation to website we have use AOS library 
    AOS Library css file cdn link -->
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

    <!-- jquery cdn link  -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
  </head>
  <body>
    <!-- portfolio section starts here -->
    <section class="portfolio" id="portfolio">
      <div class="heading text-center pt-5">
        <small>Creative Work</small>
        <h3>Check My Portfolio</h3>
      </div>

      <div id="myBtnContainer" class="text-center mt-4">
        <!-- here we will create custom attribute using data- for filtering -->
        <button class="filter-item" data-filter="all">All</button>
        <button class="filter-item" data-filter="game">Game</button>
        <button class="filter-item" data-filter="webapp">Web App</button>
        <button class="filter-item" data-filter="website">Website</button>
        <button class="filter-item" data-filter="brand">Brand</button>
      </div>
      <div class="portfolio-body">
        <div class="row justify-content-evenly px-4">
          <div class="post col-md-4 game all col-10 mt-3 mt-md-0" data-aos="fade-up">
            <div class="card">
              <img src="images/2048game.png" class="card-img-top" alt="..." />
              <div class="card-body text-center">
                <h4 class="card-title">2048 Game</h4>
                <span class="badge bg-secondary badge-pill">HTML&CSS</span>
                <span class="badge bg-secondary badge-pill">JavaScript</span>
                <span class="badge bg-secondary badge-pill mb-2">Game</span
                ><br />
                <a href="#" class="link">Read More</a>
              </div>
            </div>
          </div>
          <div class="post col-md-4 website all col-10 mt-3 mt-md-0" data-aos="fade-up">
            <div class="card">
              <img
                src="images/currency-converter.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body text-center">
                <h4 class="card-title">Converter App</h4>
                <span class="badge bg-secondary badge-pill">HTML&CSS</span>
                <span class="badge bg-secondary badge-pill">JavaScript</span>
                <span class="badge bg-secondary badge-pill mb-2">Website</span
                ><br />
                <a href="#" class="read-more-btn link">Read More</a>
              </div>
            </div>
          </div>
          <div class="post col-md-4 webapp all col-10 mt-3 mt-md-0" data-aos="fade-up">
            <div class="card">
              <img src="images/dictionary.png" class="card-img-top" alt="..." />
              <div class="card-body text-center">
                <h4 class="card-title">Dictionary</h4>
                <span class="badge bg-secondary badge-pill">HTML&CSS</span>
                <span class="badge bg-secondary badge-pill">JavaScript</span>
                <span class="badge bg-secondary badge-pill mb-2">WebApp</span
                ><br />
                <a href="#" class="read-more-btn link">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <div class="row justify-content-evenly mt-4 px-4">
          <div class="post col-md-4 game all col-10 mt-3 mt-md-0" data-aos="fade-up">
            <div class="card">
              <img src="images/piceditor.png" class="card-img-top" alt="..." />
              <div class="card-body text-center">
                <h4 class="card-title">PicEditor App</h4>
                <span class="badge bg-secondary badge-pill">HTML&CSS</span>
                <span class="badge bg-secondary badge-pill">JavaScript</span>
                <span class="badge bg-secondary badge-pill mb-2">App</span
                ><br />
                <a href="#" class="read-more-btn link">Read More</a>
              </div>
            </div>
          </div>
          <div class="post col-md-4 website all col-10 mt-3 mt-md-0" data-aos="fade-up">
            <div class="card">
              <img src="images/tictactoe.png" class="card-img-top" alt="..." />
              <div class="card-body text-center">
                <h4 class="card-title">TicTacToe Game</h4>
                <span class="badge bg-secondary badge-pill">HTML&CSS</span>
                <span class="badge bg-secondary badge-pill">JavaScript</span>
                <span class="badge bg-secondary badge-pill mb-2">Game</span
                ><br />
                <a href="#" class="read-more-btn link">Read More</a>
              </div>
            </div>
          </div>
          <div class="post col-md-4 all col-10 mt-3 mt-md-0" data-aos="fade-up">
            <div class="card">
              <img
                src="images/lang-translator.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body text-center">
                <h4 class="card-title">Lang Translator</h4>
                <span class="badge bg-secondary badge-pill">HTML&CSS</span>
                <span class="badge bg-secondary badge-pill">JavaScript</span>
                <span class="badge bg-secondary badge-pill mb-2">Web App</span
                ><br />
                <a href="#" class="read-more-btn link">Read More</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- portfolio section ends here -->

   
      <!-- bootstrap javascript cdn link  -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
      crossorigin="anonymous"
    ></script>

    <!-- AOS library javascript link  -->
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      // initializing AOS library
      AOS.init({
        duration: 1000,
        offset: 50,
      });
    </script>
    <!-- custom js file linking -->
    <script src="js/script.js"></script>
    
  </body>
</html>
