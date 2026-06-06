# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :

```
index.html

<!DOCTYPE html>
<html>
<head>
    <title>Dribbble Clone</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>

        body{
            font-family: Arial, sans-serif;
        }

        .hero{
            background-color:#ffe5ec;
            padding:80px 20px;
            text-align:center;
        }

        .hero h1{
            font-size:50px;
            font-weight:bold;
        }

        .card img{
            height:220px;
            object-fit:cover;
        }

        .feature{
            text-align:center;
            padding:20px;
        }

        .cta{
            background-color:#ff4d8d;
            color:white;
            text-align:center;
            padding:60px 20px;
        }

        footer{
            background-color:#212529;
            color:white;
            text-align:center;
            padding:20px;
        }

    </style>

</head>

<body>

<nav class="navbar navbar-expand-lg bg-light">

    <div class="container">

        <a class="navbar-brand fw-bold" href="#">
            Dribbble
        </a>

        <button class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#menu">

            <span class="navbar-toggler-icon"></span>

        </button>

        <div class="collapse navbar-collapse" id="menu">

            <ul class="navbar-nav ms-auto">

                <li class="nav-item">
                    <a class="nav-link" href="#">Explore</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Inspiration</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Hire Designers</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Sign In</a>
                </li>

                <li class="nav-item">
                    <a class="btn btn-primary ms-2" href="#">
                        Sign Up
                    </a>
                </li>

            </ul>

        </div>

    </div>

</nav>

<section class="hero">

    <div class="container">

        <h1>Discover the World's Top Designers</h1>

        <p class="lead mt-3">
            Explore creative works, connect with designers and get inspired.
        </p>

        <button class="btn btn-dark btn-lg mt-3">
            Get Started
        </button>

    </div>

</section>

<div class="container my-5">

    <h2 class="text-center mb-4">
        Featured Designs
    </h2>

    <div class="row">

        <div class="col-md-4 mb-4">

            <div class="card">

                <img src="https://picsum.photos/400/250?1">

                <div class="card-body">

                    <h5>Mobile App UI</h5>

                    <p>
                        Modern user interface design for mobile applications.
                    </p>

                </div>

            </div>

        </div>

        <div class="col-md-4 mb-4">

            <div class="card">

                <img src="https://picsum.photos/400/250?2">

                <div class="card-body">

                    <h5>Landing Page</h5>

                    <p>
                        Responsive landing page design for startup websites.
                    </p>

                </div>

            </div>

        </div>

        <div class="col-md-4 mb-4">

            <div class="card">

                <img src="https://picsum.photos/400/250?3">

                <div class="card-body">

                    <h5>Dashboard Design</h5>

                    <p>
                        Attractive dashboard design for business analytics.
                    </p>

                </div>

            </div>

        </div>

    </div>

</div>

<div class="container my-5">

    <div class="row">

        <div class="col-md-4">

            <div class="feature">

                <h3>Showcase Work</h3>

                <p>
                    Upload and share your creative projects.
                </p>

            </div>

        </div>

        <div class="col-md-4">

            <div class="feature">

                <h3>Get Inspired</h3>

                <p>
                    Discover trending designs from talented creators.
                </p>

            </div>

        </div>

        <div class="col-md-4">

            <div class="feature">

                <h3>Hire Designers</h3>

                <p>
                    Connect with professional designers worldwide.
                </p>

            </div>

        </div>

    </div>

</div>

<section class="cta">

    <h2>Ready to Start Your Design Journey?</h2>

    <p class="mt-3">
        Join thousands of designers and creative professionals today.
    </p>

    <button class="btn btn-light btn-lg">
        Join Now
    </button>

</section>

<footer>

    <p>
        © 2026 Dribbble Clone | About | Contact | Privacy Policy
    </p>

</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

```
# OUTPUT:
<img width="1919" height="1199" alt="Screenshot 2026-06-01 115218" src="https://github.com/user-attachments/assets/e49f27d5-3e02-4296-9f1c-8ac41f4b8d71" />


<img width="1919" height="1199" alt="Screenshot 2026-06-01 115226" src="https://github.com/user-attachments/assets/32bb6014-628b-4d7c-a0d0-a22b60028376" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
