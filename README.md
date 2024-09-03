<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Static Web Page</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">MyCreativeWebsite</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#home">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#features">Features</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-section d-flex align-items-center justify-content-center">
        <div class="hero-overlay">
            <div class="text-center text-white">
                <h1 class="display-4">Welcome to My Creative Web Page</h1>
                <p class="lead">An enhanced example of a static web page using HTML, CSS, and Bootstrap.</p>
                <a href="#about" class="btn btn-primary btn-lg mt-3">Learn More</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section py-5">
        <div class="container">
            <div class="row">
                <div class="col text-center">
                    <h2>About Us</h2>
                    <p class="lead">We create stunning web experiences using modern technologies.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Service Section -->
<section id="services" class="services-section py-5 bg-light">
    <div class="container">
        <div class="row text-center">
            <div class="col-md-4">
                <div class="service-box">
                    <img src="web-development-icon.png" alt="Web Development" class="service-icon">
                    <h5 class="mb-3">Web Development</h5>
                    <p>Building responsive and dynamic websites.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-box">
                    <img src="web-design-icon.png" alt="Web Design" class="service-icon">
                    <h5 class="mb-3">Web Design</h5>
                    <p>Crafting visually stunning and user-friendly designs.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-box">
                    <img src="mobile-apps-icon.png" alt="Mobile Apps" class="service-icon">
                    <h5 class="mb-3">Mobile Apps</h5>
                    <p>Creating seamless mobile applications.</p>
                </div>
            </div>
        </div>
    </div>
</section>
    <!-- Contact Section -->
    <section id="contact" class="contact-section py-5">
        <div class="container">
            <div class="row">
                <div class="col text-center">
                    <h2>Contact Us</h2>
                    <p class="lead">Get in touch with us for your next project.</p>
                    <div class="contact-details">
                        <p><img src="phone-icon.png" alt="Phone" class="contact-icon"> Tel No:+91 7702160263</p>
                        <p><img src="mail-icon.png" alt="Email" class="contact-icon"> Email Us: <a href="https://mail.google.com/mail/u/0/#inbox?compose=CllgCHrgmQMpQDnnsbwkctjZfzHHhcwMLlhNxQXLVLZzXLtClDZbQdFzQzjFjXzZvmCLkNGXNFg" target="_blank">apathrap@gitam.in</a></p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-light text-center py-3 mt-5">
        <p>&copy; 2024 Pathrapalli Akash. All rights reserved.</p>
    </footer>

    <!-- Bootstrap JS and Smooth Scroll -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>


