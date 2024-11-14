# Project Responsive Web Design using Bootstrap
## Date:14/11/24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .hero-section {
            background-image: url('bg.jpg'); 
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Inspiration</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Find Work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Learn Design</a>
                    </li>
                    <li class="nav-item">
                        <button class="btn btn-outline-primary me-2">Sign In</button>
                    </li>
                    <li class="nav-item">
                        <button class="btn btn-primary">Sign Up</button>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="hero-section">
        <h1 class="display-4 fw-bold">Discover the World's Best Designers & Creatives</h1>
        <p class="lead">Join the community and showcase your creative work.</p>
        <button class="btn btn-light btn-lg mt-3">Explore Work</button>
    </div>

    <div class="container my-5">
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350x250" class="card-img-top" alt="Design Shot 1">
                    <div class="card-body">
                        <h5 class="card-title">Recommendation 1</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350x250" class="card-img-top" alt="Design Shot 2">
                    <div class="card-body">
                        <h5 class="card-title">Recommendation 2</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350x250" class="card-img-top" alt="Design Shot 3">
                    <div class="card-body">
                        <h5 class="card-title">Recommendation 3</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="footer text-center">
        <div class="container">
            <p class="mb-0">Designed by Cynthia Mehul J</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/204a2cd3-c8c6-498e-bc59-7b17ccfc58cb)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
