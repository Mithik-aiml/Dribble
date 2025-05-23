# Project Responsive Web Design using Bootstrap
## Date:23-05-2025
## Name:Mithik jain.G
## Ref no:212224240087

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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Design Shots Gallery</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .card-img-top {
      object-fit: cover;
      height: 250px;
    }
    .navbar-brand span {
      font-weight: bold;
      color: #ea4c89;
    }
  </style>
</head>
<body>


<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#"><span>DesignShots</span></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">Shots</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
        <li class="nav-item"><a class="btn btn-pink ms-2" style="background-color:#ea4c89; color:white;">Sign Up</a></li>
      </ul>
    </div>
  </div>
</nav>


<section class="py-5 bg-light text-center">
  <div class="container">
    <h1 class="display-5">Inspiring Designs & Creative Shots</h1>
    <p class="lead">Discover amazing designs from around the world.</p>
  </div>
</section>

<section class="py-5">
  <div class="container">
    <div class="row g-4">
      <div class="col-md-4 col-sm-6">
        <div class="card h-100 shadow-sm">
          <img src="IMAGE.webp" class="card-img-top" alt="Design shot">
          <div class="card-body">
            <h5 class="card-title">PRODUCT DESIGN</h5>
            <p class="card-text">Lime Agency · 879 likes</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card h-100 shadow-sm">
          <img src="IMAGE1.webp" class="card-img-top" alt="Design shot">
          <div class="card-body">
            <h5 class="card-title">MOBILE</h5>
            <p class="card-text">Purrweb UI/UX Agency · 131 likes</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card h-100 shadow-sm">
          <img src="IMAGE2.webp" class="card-img-top" alt="Design shot">
          <div class="card-body">
            <h5 class="card-title">WEB DESIGN</h5>
            <p class="card-text">Gapsy Studio · 5.2k likes</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<footer class="bg-dark text-white text-center py-3 mt-5">
  <div class="container">
    <p class="mb-0">&copy; 2025 DesignShots. All rights reserved.</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```



## OUTPUT:

![Screenshot 2025-05-23 114010](https://github.com/user-attachments/assets/7cbfa0fb-bc4b-49ff-ac2a-a39bee658c80)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
