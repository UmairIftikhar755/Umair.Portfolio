# Umair.Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umair Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <!-- AOS library link -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body>
<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-dark ">
    <a class="navbar-brand" href="#"><span class="navi">My Portfolio</span></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a class="nav-link" href="#header"><span class="navi">Home</span></a></li>
            <li class="nav-item"><a class="nav-link" href="#education"><span class="navi">Education</span></a></li>
            <li class="nav-item"><a class="nav-link" href="#skills"><span class="navi">Skills</span></a></li>
            <li class="nav-item"><a class="nav-link" href="#experience"><span class="navi">Experience</span></a></li>
            <li class="nav-item"><a class="nav-link" href="#projects"><span class="navi">Projects</span></a></li>
            <li class="nav-item"><a class="nav-link" href="#contact"><span class="navi">Contact </span></a></li>
        </ul>
    </div>
</nav>

<!-- Header -->
<header id="header" class=" jumbotron ">
<div class="row">
    <div class="col-md-3">

    </div>
    <div class="col-md-2">

        <img style="height: 190px; width: 150px;" src="my.jpg">
    </div>
    <div class="col-md-4">
    <h1 class="display-3">Umair Iftikhar</h1>
    <p class="lead">Web Developer & Designer</p>
    <a href="#contact" class="btn btn-dark">Contact Me</a>
</header>
</div>
</div>
<div data-aos="fade-right">
<!-- Education Section -->
<section id="education" class="container my-5">
    <u><h2 class="text-center">Education</h2></u>
    <br><br>
    <div class="row">
        <div class="col-md-4">
            <h3>School Of Matriculation</h3>
            <p>Unique High School, 2016 - 2020</p>
        </div>
        <div class="col-md-4">
            <h3>School of Intermediate</h3>
            <p>Punjab College, 2020 - 2022</p>
        </div>
        <div class="col-md-4">
            <h3>Bachelor's in Computer Science</h3>
            <p>University of Managment and Technology, 2022 - 2024</p>
        </div>
    </div>
</section>
</div>
<div data-aos="fade-right">
<!-- Skills Section -->
<section id="skills" class="bg-light py-5">
    <div class="container">
        <u><h2 class="text-center">Skills</h2></u>
        <br><br>
        <div class="row">
            <div class="col-md-4">
                <h4>Frontend</h4>
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>React</li>
                </ul>
            </div>
            <div class="col-md-4">
                <h4>Backend</h4>
                <ul>
                    <li>Node.js</li>
                    <li>Express</li>
                    <li>Python</li>
                    <li>Django</li>
                </ul>
            </div>
            <div class="col-md-4">
                <h4>Other</h4>
                <ul>
                    <li>Git</li>
                    <li>SQL</li>
                    <li>Docker</li>
                    <li>AWS</li>
                </ul>
            </div>
        </div>
    </div>
</section>
</div>
<div data-aos="fade-right">
<!-- Experience Section -->
<section id="experience" class="container my-5">
    <u><h2 class="text-center">Experience</h2></u>
    <br><br>
    <div class="row">
        <div class="col-md-6">
            <h3>Web Developer</h3>
            <p>Systems Software,  Present</p>
            <ul>
                <li>Developed and maintained company website</li>
                <li>Collaborated with designers and backend developers</li>
                <li>Implemented responsive design</li>
            </ul>
        </div>
        <div class="col-md-6">
            <h3>Intern</h3>
            <p>ERA Flip, Summer </p>
            <ul>
                <li>Assisted in developing web applications</li>
                <li>Performed testing and debugging</li>
                <li>Contributed to code reviews</li>
            </ul>
        </div>
    </div>
</section>
</div>
<div data-aos="fade-right">
<!-- Projects Section -->
<section id="projects" class="bg-light py-5">
    <div class="container">
        <u><h2 class="text-center">Projects</h2></u>
        <br><br>
        <div class="row">
            <div class="col-md-4">
                <h4>Automotive 24/7</h4>
                <p>A web application that provides a wide range of Automotive services like car maintenance and car wash etc.</p>
                <a href="https://example.com/demo" class="btn btn-outline-primary">View Project</a>

            </div>
            <div class="col-md-4">
                <h4>Sasta Bazar</h4>
                <p>An e-commerce platform for online shopping.</p>

            </div>
            <div class="col-md-4">
                <h4>Doctors Anywhere</h4>
                <p>A service website that provides a list of Specialist Doctors which or where they can provide their practices and people can take appointments very easily at available time.</p>
                
            </div>
        </div>
    </div>
</section>
</div>
<div data-aos="fade-right">
<!-- Contact Section -->
<section id="contact" class="container my-5">
    <u><h2 class="text-center">Contact Me</h2></u>
    <br><br>
    <form>
        <div class="form-group">
            <label for="name">Name</label>
            <input type="text" class="form-control" id="name" placeholder="Your Name">
        </div>
        <div class="form-group">
            <label for="email">Email address</label>
            <input type="email" class="form-control" id="email" placeholder="Your Email">
        </div>
        <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="3" placeholder="Your Message" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
    </form>
</section>
</div>
<!-- Footer -->
<footer class="text-center py-4">
    <p>2024 Umair Iftikhar. All Rights Reserved.</p>
</footer>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
    AOS.init();
</script>
</body>
</html>
