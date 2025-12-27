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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom Pastel Styling */
    body {
      font-family: 'Arial', sans-serif;
      background-color: #fdfdfd;
    }
    .navbar {
      background-color: #ffebee; /* Soft pink */
    }
    .navbar-brand, .nav-link {
      color: #3f51b5 !important; /* Deep blue */
    }
    .hero-section {
      background: linear-gradient(135deg, #e3f2fd, #fce4ec); /* Pastel blue to pink */
      color: #4a148c; /* Deep purple */
    }
    .hero-section h1 {
      font-size: 3rem;
    }
    .btn-primary {
      background-color: #80deea; /* Light teal */
      border-color: #80deea;
    }
    #features {
      background-color: #f3e5f5; /* Soft lavender */
    }
    .feature-icon {
      color: #ff7043; /* Pastel orange */
    }
    #gallery {
      background-color: #e8f5e9; /* Light mint green */
    }
    img {
      border: 3px solid #ffcdd2; /* Pastel pink border */
    }
    footer {
      background-color: #fce4ec; /* Pastel pink */
      color: #4a148c; /* Deep purple */
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#gallery">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero-section text-center py-5">
    <h1>Welcome to Dribbble Clone</h1>
    <p class="lead">Discover amazing pastel-themed designs and share your own.</p>
    <a href="#gallery" class="btn btn-primary">Explore Now</a>
  </div>

  <!-- Features Section -->
  <section id="features" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Features</h2>
      <div class="row">
        <div class="col-md-4 text-center">
          <i class="bi bi-palette-fill feature-icon fs-1"></i>
          <h4>Creative Designs</h4>
          <p>Find thousands of inspiring designs from creative professionals.</p>
        </div>
        <div class="col-md-4 text-center">
          <i class="bi bi-share-fill feature-icon fs-1"></i>
          <h4>Share Your Work</h4>
          <p>Upload and showcase your projects to a global audience.</p>
        </div>
        <div class="col-md-4 text-center">
          <i class="bi bi-heart-fill feature-icon fs-1"></i>
          <h4>Build a Community</h4>
          <p>Connect with designers and get valuable feedback.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Gallery</h2>
      <div class="row g-3">
        <div class="col-md-4">
          <img src="Screenshot 2025-05-16 175350.png" class="img-fluid rounded" alt="Design 1">
        </div>
        <div class="col-md-4">
          <img src="Screenshot 2025-05-16 175416.png" class="img-fluid rounded" alt="Design 2">
        </div>
        <div class="col-md-4">
          <img src="Screenshot 2025-05-16 175444.png" class="img-fluid rounded" alt="Design 3">
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-3">
    <p>&copy; C Dharshan </p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```




# OUTPUT:
<img width="1890" height="986" alt="Screenshot 2025-05-16 175819" src="https://github.com/user-attachments/assets/4acb49e7-0923-4cb7-b251-0cf68dbd9796" />

<img width="1897" height="975" alt="Screenshot 2025-05-16 175831" src="https://github.com/user-attachments/assets/9e78d2aa-1340-4872-99fe-b0f834ca4d68" />


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
