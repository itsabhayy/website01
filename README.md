# website01
its about my About me Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="itsabhayy, portfolio, Abhay, full stack dev, personal portfolio lifecodes, portfolio design, portfolio website, personal portfolio" />
    <meta name="description" content="Welcome to Abhay's Portfolio. Full-Stack Web Developer and Android App Developer" />
    <!-- Custom CSS -->
    <link rel="stylesheet" href="./assets/css/style.css">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- Favicon -->
    <link id='favicon' rel="shortcut icon" href="./assets/images/favicon.png" type="image/x-png">
    <title>@itsabhayy</title>

    <style>
      /* Custom hover effect for images */
      .card-img-top {
        transition: transform 0.3s ease, filter 0.3s ease;
      }

      .card-img-top:hover {
        transform: scale(1.05); /* Zoom effect */
        filter: brightness(80%); /* Darken effect */
        cursor: pointer;
      }

      /* To remove extra space on card body clicks */
      .card {
        overflow: hidden;
      }
    </style>
</head>
<body oncontextmenu="return false">

<!-- pre loader -->
<!-- <div class="loader-container">
  <img draggable="false" src="./assets/images/preloader.gif" alt="">
</div> -->

<!-- navbar starts -->
<header>
    <a href="/" class="logo"><i class="favhand.png"></i> Abhay</a>
    <div id="menu" class="fas fa-bars"></div>
    <nav class="navbar">
        <ul>
            <li><a class="active" href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#work">Work</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>
<!-- navbar ends -->

<!-- hero section starts -->
<section class="home" id="home">
    <div id="particles-js"></div>
    <div class="content">
        <h2>Hi There,<br/> I'm Abhay <span></span></h2>
        <p>i am into <span class="typing-text"></span></p>
        <a href="#about" class="btn"><span>About Me</span>
            <i class="fas fa-arrow-circle-down"></i>
        </a>
        <div class="socials">
            <ul class="social-icons">
                <li><a class="linkedin" aria-label="LinkedIn" href="https://www.linkedin.com/in/itsabhayy/" target="_blank"><i class="fab fa-linkedin"></i></a></li>
                <li><a class="github" aria-label="GitHub" href="https://github.com/itsabhayy" target="_blank"><i class="fab fa-github"></i></a></li>
                <li><a class="twitter" aria-label="Twitter" href="https://twitter.com/itsabhayy" target="_blank"><i class="fab fa-twitter"></i></a></li>
                <li><a class="telegram" aria-label="Telegram" href="https://t.me/itsabhay01" target="_blank"><i class="fab fa-telegram-plane"></i></a></li>
                <li><a class="instagram" aria-label="Instagram" href="https://www.instagram.com/itsabhayy"><i class="fab fa-instagram" target="_blank"></i></a></li>
                <li><a class="dev" aria-label="Dev" href="https://dev.to/itsabhayy" target="_blank"><i class="fab fa-dev"></i></a></li>
            </ul>
        </div>
    </div>
    <div class="image">
        <img draggable="false" class="tilt" src="./assets/images/hero.png" alt="">
    </div>
</section>
<!-- hero section ends -->

<!-- about section starts -->
<section class="about" id="about">
    <h2 class="heading"><i class="fas fa-user-alt"></i> About <span>Me</span></h2>

    <div class="row">
        <div class="image">
            <img draggable="false" class="tilt" src="./assets/images/profile2.jpg" alt="">
        </div>
        <div class="content">
            <h3>I'm Abhay</h3>
            <span class="tag">Full Stack Developer, Cybersecurity Analyst, Data Analyst</span>

            <p>Hi, I’m Abhay, a 2nd-year Computer Science Engineering student specializing in Cybersecurity. I enjoy exploring technology and crafting solutions that address real-world challenges.</p>
            <p>I have experience in:</p>

            <ul>
                <li><strong>Cybersecurity:</strong>&nbsp; Enhancing digital safety and securing systems.</li>
                <li><strong>Artificial Intelligence:</strong>&nbsp; Developing smart systems that learn and adapt.</li>
                <li><strong>Data Science:</strong>&nbsp; Analyzing data to uncover meaningful insights.</li>
                <li><strong>Web Development:</strong>&nbsp; Designing and building efficient, user-friendly websites.</li>
            </ul>
            <p>Driven by curiosity and innovation, I’m committed to building impactful projects and staying ahead in the ever-evolving tech world. Let’s collaborate and make a difference!</p>

            <div class="box-container">
                <div class="box">
                    <p><span>email:</span> emailtoabhay01@gmail.com</p>
                    <p><span>place:</span> Jammu, India - 181143</p>
                </div>
            </div>

            <div class="resumebtn">
                <a href="https://drive.google.com/file/d/1-7IV8BWysoXPDVKyS5bWDIE9uALIGeGE/view?usp=drive_link" target="_blank" class="btn"><span>Resume</span>
                    <i class="fas fa-chevron-right"></i>
                </a>
            </div>
        </div>
    </div>
</section>
<!-- about section ends -->

<!-- education section starts -->
<section class="education" id="education">
    <h1 class="heading"><i class="fas fa-graduation-cap"></i> My <span>Education</span></h1>

    <p class="qoute">Education is not the learning of facts, but the training of the mind to think.</p>

    <div class="box-container">
        <div class="box">
            <div class="image">
                <img draggable="false" src="./assets/images/educat/college.jpg" alt="">
            </div>
            <div class="content">
                <h3>Bachelor of Technology in CSE(cyber security)</h3>
                <p>Central university of Jammu | CUJ</p>
                <h4>2023-2027 | Pursuing</h4>
            </div>
        </div>

        <div class="box">
            <div class="image">
                <img draggable="false" src="./assets/images/educat/school.jpg" alt="">
            </div>
            <div class="content">
                <h3>Class XI & XII</h3>
                <p>Modern Group of Schools| CBSE</p>
                <h4>2020-2022 | Completed</h4>
            </div>
        </div>
    </div>
</section>
<!-- education section ends -->

<!-- portfolio section starts here -->
<section class="portfolio" id="portfolio">
    <div class="heading text-center pt-5">
        <small>Creative Work</small>
        <h3>Check My Portfolio</h3>
    </div>

    <div id="myBtnContainer" class="text-center mt-4">
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
                    <a href="https://github.com/

