# Project Responsive Web Design using Bootstrap
## Date:13.05.24

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
pharmacy.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmacy Website</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS can go here */
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">CurePharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="pharmacy.html">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="about.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="contact.html">Contact</a>
      </li>
    </ul>
  </div>
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <div class="row">
    <div class="col-md-8">
      <h2>Welcome to CurePharmacy</h2>
      <p>Medicating with compassion . Curing with care.</p>
    </div>
    <div class="col-md-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Opening Hours</h5>
          <p class="card-text">Monday - Friday: 8:00 AM - 8:00 PM</p>
          <p class="card-text">Saturday: 10:00 AM - 6:00 PM</p>
          <p class="card-text">Sunday: Closed</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container text-center">
    <p>&copy; 2024 Pharmacy. All rights reserved.</p><br>
    <p>Developed by Jesu Smartia A (212222110016)</p>
  </div>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>

about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - CurePharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS for Pharmacy Website */

    /* Navbar */
    .navbar {
      border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .navbar-brand {
      font-weight: bold;
    }

    /* Main Content */
    .container {
      padding-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
    }

    /* Responsive styles */
    @media (max-width: 768px) {
      .container {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">CurePharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="pharmacy.html">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="about.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="contact.html">Contact</a>
      </li>
    </ul>
  </div>
  <!-- Rest of the navbar code -->
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <!-- About content -->
  <h2>About CurePharmacy</h2>
  <p>Welcome to CurePharmacy, your trusted neighborhood pharmacy dedicated to provide high-quality healthcare services and products. Our team of experienced pharmacists and staff are here to serve you with care and expertise.</p>
  <img src="phar1.jpg" alt="Pharmacy Image" class="img-fluid mt-4" height="400" width="400">
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5>Contact Us</h5>
        <p>Address: 103 Anna Nagar, Chennai</p>
        <p>Phone: 823-756-0890</p>
        <p>Email: info@curepharmacy.com</p>
      </div>
      <div class="col-md-6">
        <h5>Follow Us</h5>
        <p>Stay connected with us on social media for updates and health tips.</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#"><img src="fb.png" alt="Facebook" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="twit.png" alt="Twitter" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="ig.jpg" alt="Instagram" height="30" width="30"></a></li>
        </ul>
      </div>
    </div>
  </div>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>

service.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Services - CurePharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS for Pharmacy Website */

    /* Navbar */
    .navbar {
      border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .navbar-brand {
      font-weight: bold;
    }

    /* Main Content */
    .container {
      padding-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
    }

    /* Responsive styles */
    @media (max-width: 768px) {
      .container {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">CurePharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="pharmacy.html">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="ABOUTP.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="contact.html">Contact</a>
      </li>
    </ul>
  </div>
  <!-- Rest of the navbar code -->
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <!-- Services content -->
  <h2>Our Services</h2>
  <p>At CurePharmacy, we offer a wide range of services to cater to your healthcare needs:</p>
  <ul>
    <li>Prescription filling and medication counseling</li>
    <li>Over-the-counter medications and health products</li>
    <li>Health screenings and vaccinations</li>
    <li>Medication therapy management</li>
    <li>Home delivery services</li>
    <li>Compounding services</li>
  </ul>
  
  
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5>Contact Us</h5>
        <p>Address: 103 Anna Nagar, Chennai</p>
        <p>Phone: 823-756-0890</p>
        <p>Email: info@curepharmacy.com</p>
      </div>
      <div class="col-md-6">
        <h5>Follow Us</h5>
        <p>Stay connected with us on social media for updates and health tips.</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#"><img src="fb.png" alt="Facebook" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="twit.png" alt="Twitter" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="ig.jpg" alt="Instagram" height="30" width="30"></a></li>
        </ul>
      </div>
    </div>
  </div>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - CurePharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS for Pharmacy Website */

    /* Navbar */
    .navbar {
      border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .navbar-brand {
      font-weight: bold;
    }

    /* Main Content */
    .container {
      padding-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
    }

    /* Responsive styles */
    @media (max-width: 768px) {
      .container {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="pharmacy.html">CurePharmacy</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="about.html">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="service.html">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="contact.html">Contact</a>
      </li>
    </ul>
  </div>
  <!-- Rest of the navbar code -->
</nav>

<!-- Main Content -->
<div class="container mt-4">
  <!-- Contact Form -->
  <h2>Contact Us</h2>
  <p>If you have any questions or inquiries, please feel free to contact us using the form below:</p>
  <form>
    <div class="form-group">
      <label for="name">Name:</label>
      <input type="text" class="form-control" id="name" placeholder="Enter your name">
    </div>
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" class="form-control" id="email" placeholder="Enter your email">
    </div>
    <div class="form-group">
      <label for="message">Message:</label>
      <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</div>

<!-- Footer -->
<footer class="bg-dark text-white mt-5 py-4">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5>Contact Us</h5>
        <p>Address: 103 Anna Nagar, Chennai </p>
        <p>Phone: 814-756-0890</p>
        <p>Email: info@curepharmacy.com</p>
      </div>
      <div class="col-md-6">
        <h5>Follow Us</h5>
        <p>Stay connected with us on social media for updates and health tips.</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#"><img src="fb.png" alt="Facebook" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="twit.png" alt="Twitter" height="30" width="30"></a></li>
          <li class="list-inline-item"><a href="#"><img src="ig.jpg" alt="Instagram" height="30" width="30"></a></li>
        </ul>
      </div>
    </div>
  </div>
  <center>Developed By Jesu Smartia A (212222110016)</center>
</footer>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>

```


## OUTPUT:

![Screenshot 2024-05-14 100648](https://github.com/jesu-smartia05/Pharma/assets/148514819/1277435d-c9b0-4eed-8c12-929ce9b44aa2)

![Screenshot 2024-05-14 101203](https://github.com/jesu-smartia05/Pharma/assets/148514819/9ed90513-fe6e-4e3f-8095-c7e1859f63fe)

![Screenshot 2024-05-14 101517](https://github.com/jesu-smartia05/Pharma/assets/148514819/49aec19e-ec6e-41d0-9781-8c4939259d96)

![Screenshot 2024-05-14 101549](https://github.com/jesu-smartia05/Pharma/assets/148514819/1a180256-4a1c-4541-bc8a-a15b583b553e)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
