# Project Responsive Web Design using Bootstrap
## Date:25/12/2024

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
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    
    <!-- Google Font for Pacifico -->
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Content Section -->
    <div class="container mt-4">
        <div class="text-center mb-4 header-section">
            <h3>What are you working on?</h3>
            <p class="lead">"Create, Collaborate, Inspire, Repeat"</p>
        </div>

        <!-- Gallery Section -->
        <div class="row gallery-section">
            <!-- Gallery Items (8 items in total) -->
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img1.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">Santa Maria</p>
                        <small class="text-muted">DESIGN 1</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img2.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">Michael Bierut</p>
                        <small class="text-muted">DESIGN 2</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img3.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">
                            Louise Fili</p>
                        <small class="text-muted">DESIGN 3</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img4.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">William Golden</p>
                        <small class="text-muted">DESIGN 4</small>
                    </div>
                </div>
            </div>
            <!-- Additional Gallery Items -->
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img5.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">Josef Muller</p>
                        <small class="text-muted">DESIGN 5</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img6.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title"> Susan Kare</p>
                        <small class="text-muted">DESIGN 6</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img7.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">Jessica Walsh</p>
                        <small class="text-muted">DESIGN 7</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="img8.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail" height="150">
                    <div class="card-body text-center">
                        <p class="card-title">Paula Scher</p>
                        <small class="text-muted">DESIGN 8</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed and developed by Hiba Nasreen M</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-25 215251-1.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
