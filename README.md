# Project Responsive Web Design using Bootstrap
## Date:24/12/2024

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
    <title>Explore Nature</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-success">

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Beauty of Nature</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Gallery</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
                <ul class="navbar-nav mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Log In</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-light text-dark px-3" href="#">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header -->
    <div class="bg-dark text-light text-center py-5">
        <h1 class="display-4 fw-bolder">Beauty of Nature</h1>
        <p class="lead">"Discover the beauty of nature and its hidden gems!"</p>
    </div>

    <!-- Categories -->
    <div class="container my-5">
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card shadow-sm rounded">
                        <img src="ai-generated-ai-generative-outdoor-nature-adventure-forest-walk-path-road-adventures-background-graphic-art-photo.jpg" class="card-img-top" alt="Forests">
                        <div class="card-body">
                            <h5 class="card-title">Forests</h5>
                            <p class="card-text">Explore the lush greenery and biodiversity of our forests.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card shadow-sm rounded">
                        <img src="mountain.jpg" class="card-img-top" alt="Mountains">
                        <div class="card-body">
                            <h5 class="card-title">Mountains</h5>
                            <p class="card-text">Experience the majestic peaks and scenic views of nature's heights.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card shadow-sm rounded">
                        <img src="river.jpg" class="card-img-top" alt="Rivers">
                        <div class="card-body">
                            <h5 class="card-title">Rivers</h5>
                            <p class="card-text">Discover the serenity of flowing rivers and their tranquil beauty.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card shadow-sm rounded">
                        <img src="wildlife.png" class="card-img-top" alt="Wildlife">
                        <div class="card-body">
                            <h5 class="card-title">Wildlife</h5>
                            <p class="card-text">Get a closer look at the incredible animals of the wild.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card shadow-sm rounded">
                        <img src="beach.jpeg" class="card-img-top" alt="Beaches">
                        <div class="card-body">
                            <h5 class="card-title">Beaches</h5>
                            <p class="card-text">Relax on pristine beaches with golden sands and blue waters.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card shadow-sm rounded">
                        <img src="desert.webp" class="card-img-top" alt="Deserts">
                        <div class="card-body">
                            <h5 class="card-title">Deserts</h5>
                            <p class="card-text">Experience the vast expanse of serene deserts and their unique charm.</p>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="text-center py-3 bg-light">
        <p>&copy; 2024 One touch of nature makes the whole world.</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![Screenshot (5)](https://github.com/user-attachments/assets/40e84910-e958-4b59-9d53-2a5e0eb13e42)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
