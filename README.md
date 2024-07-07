<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Unique Webpage</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <a href="#" class="navbar-brand">My Webpage</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#features">Features</a></li>
                        <li class="nav-item"><a class="nav-link" href="#testimonials">Testimonials</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <section id="home" class="hero text-center text-white d-flex align-items-center">
        <div class="container">
            <h1 class="display-4">Welcome to My Unique Webpage</h1>
            <p>Your solution for product management</p>
            <a href="#features" class="btn btn-success">Learn More</a>
        </div>
    </section>
    <section id="features" class="py-5">
        <div class="container">
            <h2 class="text-center">Features</h2>
            <div class="row">
                <div class="col-md-4">
                    <h3>Feature 1</h3>
                    <p>Description of feature 1.</p>
                </div>
                <div class="col-md-4">
                    <h3>Feature 2</h3>
                    <p>Description of feature 2.</p>
                </div>
                <div class="col-md-4">
                    <h3>Feature 3</h3>
                    <p>Description of feature 3.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="testimonials" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Testimonials</h2>
            <div class="row">
                <div class="col-md-6">
                    <blockquote class="blockquote">
                        <p class="mb-0">"This is the best product ever!"</p>
                        <footer class="blockquote-footer">Happy Customer</footer>
                    </blockquote>
                </div>
                <div class="col-md-6">
                    <blockquote class="blockquote">
                        <p class="mb-0">"I can't imagine my life without it."</p>
                        <footer class="blockquote-footer">Satisfied User</footer>
                    </blockquote>
                </div>
            </div>
        </div>
    </section>
    <footer id="contact" class="py-4 bg-dark text-white text-center">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: info@mywebpage.com</p>
            <p>Phone: +123 456 7890</p>
            <p>&copy; 2024 My Unique Webpage. All rights reserved.</p>
        </div>
    </footer>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
