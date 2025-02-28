<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samprity Singha | Portfolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="css/styles.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="js/script.js" defer></script>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
        }
        .hero-section {
            background: url('img/hero-bg.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .animate-slide {
            animation: slideUp 1.5s ease-in-out;
        }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .card {
            background-color: #1e1e1e;
            color: #ffffff;
        }
        .card:hover {
            transform: scale(1.05);
            transition: 0.3s ease-in-out;
            box-shadow: 0px 10px 20px rgba(255, 255, 255, 0.3);
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">PORTFOLIO</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#expertise">Expertise</a></li>
                    <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero-section text-center text-white d-flex align-items-center">
        <div class="container">
            <h1 class="animate-fade">Samprity Singha</h1>
            <p class="lead animate-slide">B.Tech in Computer Science and Engineering (Data Science)</p>
        </div>
    </header>

    <section id="about" class="container mt-5 text-center">
        <h2>About Me</h2>
        <img src="img/profile.jpg" class="rounded-circle" width="150" alt="Samprity Singha">
        <p>I am a passionate computer science student with a keen interest in data analysis, machine learning, and programming. Always eager to learn and explore new technologies.This is my portfolio:
        </p>
    </section>

    <section id="expertise" class="container mt-5">
        <h2 class="text-center">Expertise</h2>
        <ul>
            <li>Data Analysis & Machine Learning</li>
            <li>Programming Languages: Python, Java, R, HTML</li>
            <li>Deep Learning & Predictive Analytics</li>
            <li>Front-End & Full-Stack Development</li>
        </ul>
    </section>

    <section id="education" class="container mt-5 text-center">
        <h2>Education</h2>
        <p>B.Tech in Computer Science and Engineering (Data Science)</p>
        <p>Presidency University, Bangalore</p>
    </section>

    <section id="projects" class="container mt-5">
        <h2 class="text-center">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="img/project1.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title">Biometric Encryption</h5>
                        <p class="card-text">Developed a secure biometric encryption method using an iris and face scan to prevent privacy attacks.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="container mt-5 text-center">
        <h2>Contact Me</h2>
        <p>Email: samprity@gmail.com</p>
        <p>LinkedIn: <a href="#">linkedin.com/in/samprity</a></p>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
