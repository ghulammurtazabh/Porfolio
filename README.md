<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ghulam Murtaza | Developer Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f8f9fa;
      color: #333;
      scroll-behavior: smooth;
    }

    nav {
      background-color: #ffffff;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    nav a {
      color: #333;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #007bff;
    }

    header {
      padding: 8rem 2rem 5rem;
      background: linear-gradient(to right, #74ebd5, #acb6e5);
      text-align: center;
      color: #fff;
    }

    .profile-img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 4px solid #fff;
      object-fit: cover;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.2);
    }

    .section-title {
      font-size: 2.5rem;
      margin-bottom: 2rem;
      position: relative;
      color: #007bff;
      text-align: center;
    }

    .section-title::after {
      content: '';
      width: 80px;
      height: 4px;
      background: #007bff;
      position: absolute;
      bottom: -10px;
      left: 50%;
      transform: translateX(-50%);
    }

    section {
      padding: 6rem 2rem;
    }

    .card-custom {
      background-color: #ffffff;
      border: 2px solid #007bff;
      border-radius: 15px;
      padding: 1.5rem;
      text-align: center;
      font-weight: 600;
      transition: all 0.4s ease;
    }

    .card-custom:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 20px rgba(0,123,255,0.3);
    }

    #projects {
      background: #f1f3f5;
    }

    .project-card {
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.05);
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-8px);
    }

    #contact {
      background: #e9ecef;
      text-align: center;
    }

    .social-icons a {
      color: #007bff;
      font-size: 1.5rem;
      margin: 0 10px;
      transition: 0.3s;
    }

    .social-icons a:hover {
      color: #0056b3;
    }

    footer {
      padding: 2rem;
      text-align: center;
      background: #f8f9fa;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#home">Ghulam</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <header id="home">
    <div class="container">
      <img src="IMG_2782.jpg" alt="Ghulam Murtaza" class="profile-img mb-3" data-aos="zoom-in">
      <h1 class="display-4 fw-bold" data-aos="fade-up">Ghulam Murtaza</h1>
      <p class="lead" data-aos="fade-up" data-aos-delay="200">Full Stack Developer | ASP.NET Core | SQL | UI/UX | SQA</p>
    </div>
  </header>

  <section id="skills">
    <div class="container">
      <h2 class="section-title" data-aos="fade-right">My Skills</h2>
      <div class="row">
        <div class="col-md-4 mb-4" data-aos="flip-left"><div class="card card-custom">ASP.NET Core MVC</div></div>
        <div class="col-md-4 mb-4" data-aos="flip-left"><div class="card card-custom">SQL & Database Design</div></div>
        <div class="col-md-4 mb-4" data-aos="flip-left"><div class="card card-custom">HTML5 / CSS3</div></div>
        <div class="col-md-4 mb-4" data-aos="flip-left"><div class="card card-custom">JavaScript / jQuery</div></div>
        <div class="col-md-4 mb-4" data-aos="flip-left"><div class="card card-custom">Software Quality Assurance</div></div>
        <div class="col-md-4 mb-4" data-aos="flip-left"><div class="card card-custom">UI/UX Design</div></div>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2 class="section-title" data-aos="fade-left">Projects</h2>
      <div class="row">
        <div class="col-md-6 mb-4" data-aos="fade-up">
          <div class="card project-card p-4">
            <h5 class="fw-bold">E-Commerce Website</h5>
            <p>ASP.NET Core MVC project with admin panel, product catalog, user login, cart, and order management system.</p>
          </div>
        </div>
        <div class="col-md-6 mb-4" data-aos="fade-up" data-aos-delay="100">
          <div class="card project-card p-4">
            <h5 class="fw-bold">Quiz Web App</h5>
            <p>Online quiz system built with React Native & Node.js backend, featuring timed tests and score tracking.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2 class="section-title" data-aos="fade-right">About Me</h2>
      <p data-aos="fade-up">I am a dedicated developer based in Karachi with a BCS degree from KIET University. I bring ideas to life with clean code, modern UI, and backend logic. My focus lies in delivering high-quality, scalable applications that solve real-world problems.</p>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2 class="section-title" data-aos="zoom-in">Contact</h2>
      <p data-aos="fade-up">Let’s collaborate! Reach out to me:</p>
      <a href="mailto:mirmurtazarf8900@gmail.com" class="btn btn-outline-primary mt-3" data-aos="fade-up" data-aos-delay="200">mirmurtazarf8900@gmail.com</a>
      <div class="social-icons mt-4" data-aos="fade-up" data-aos-delay="300">
        <a href="#"><i class="fab fa-linkedin"></i></a>
        <a href="#"><i class="fab fa-github"></i></a>
        <a href="#"><i class="fab fa-facebook"></i></a>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Ghulam Murtaza | Made with <i class="fas fa-heart text-danger"></i>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
  <script>
    AOS.init({ once: true, duration: 1000 });
  </script>
</body>
</html>
