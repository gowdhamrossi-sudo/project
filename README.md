# Project Responsive Web Design using Bootstrap
# Date:19.05.2025
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
Dribbble page.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Dribbble</a>
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
                        <a class="btn btn-primary" href="LOGIN.HTML" target="_blank">login</a>
        
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container-fluid bg-info text-center py-5">
        <h1 class="display-4">Discover the World’s Top Designers & Creative Professionals</h1>
        <p class="lead">Dribbble is where designers gain inspiration, feedback, and find jobs.</p>
        <button class="btn btn-primary btn-lg">Explore Work</button>
    </div>

    <div class="container my-5">
        <h2 class="text-center mb-4">Featured Work</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="1.avif" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Design 1</h5>
                        <p class="card-text">A beautiful representation of creativity.</p>
                        <button class="btn btn-outline-primary me-2">Like</button>
                        <button class="btn btn-outline-secondary">Comment</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="2.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Design 2</h5>
                        <p class="card-text">An innovative approach to modern design.</p>
                        <button class="btn btn-outline-primary me-2">Like</button>
                        <button class="btn btn-outline-secondary">Comment</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="3.avif" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Design 3</h5>
                        <p class="card-text">An innovative approach to modern design.</p>
                        <button class="btn btn-outline-primary me-2">Like</button>
                        <button class="btn btn-outline-secondary">Comment</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="4.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Design 4</h5>
                        <p class="card-text">An innovative approach to modern design.</p>
                        <button class="btn btn-outline-primary me-2">Like</button>
                        <button class="btn btn-outline-secondary">Comment</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="5.avif" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Design 5</h5>
                        <p class="card-text">An innovative approach to modern design.</p>
                        <button class="btn btn-outline-primary me-2">Like</button>
                        <button class="btn btn-outline-secondary">Comment</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="6.avif" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Design 6</h5>
                        <p class="card-text">A fresh perspective on creative art.</p>
                        <button class="btn btn-outline-primary me-2">Like</button>
                        <button class="btn btn-outline-secondary">Comment</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="container my-5">
        <div class="row">
            <div class="col-md-4 text-center">
                <img src="7.webp" class="rounded-circle mb-3" alt="..." width="200" height="200">
                <h5>Explore Designs</h5>
                <p>Find creative inspiration for your next project.</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="8.jpg" class="rounded-circle mb-3" alt="..." width="200" height="200">
                <h5>Connect with Cars</h5>
                <p>Collaborate with top  Car designers around the globe.</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="9.webp" class="rounded-circle mb-3" alt="..." width="200" height="200">
                <h5>Grow Your Skills</h5>
                <p>Access learning resources to improve your craft.</p>
            </div>
        </div>
    </div>
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 Dribbble . All Rights Reserved.</p>
            <p>
                <a href="#" class="text-white me-3">Privacy Policy</a>
                <a href="#" class="text-white">Terms of Service</a>
            </p>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
Login page.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #20c997, #6f42c1);
            color: #fff;
        }
        .container {
            background: #f9f9f9;
            color: #333;
            border-radius: 10px;
            padding: 35px;
            width: 400px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        h2 {
            margin-bottom: 20px;
        }
        form {
            text-align: left;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            font-size: 14px;
            margin-bottom: 5px;
            color: #444;
        }
        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        .forgot-password {
            text-align: right;
            margin-bottom: 20px;
        }
        .forgot-password a {
            text-decoration: none;
            font-size: 12px;
            color: #6f42c1;
        }
        .btn {
            background: linear-gradient(135deg, #20c997, #6f42c1);
            border: none;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            width: 100%;
            cursor: pointer;
            font-size: 16px;
        }
        .social-login {
            margin-top: 20px;
        }
        .social-login p {
            font-size: 14px;
            margin-bottom: 10px;
            color: #555;
        }
        .social-login .icons {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .social-login .icons a {
            text-decoration: none;
            color: #fff;
            font-size: 18px;
            width: 35px;
            height: 35px;
            line-height: 35px;
            border-radius: 50%;
            text-align: center;
        }
        .social-login .icons .facebook {
            background-color: #1877f2;
        }
        .social-login .icons .google {
            background-color: #ea4335;
        }
        .signup {
            font-size: 14px;
            margin-top: 15px;
        }
        .signup a {
            text-decoration: none;
            color: #6f42c1;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Login</h2>
        <form action="#">
            <div class="form-group">
                <label for="username">Username</label>
                <input type="text" id="username" placeholder="Type your username" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" placeholder="Type your password" required>
            </div>
            <div class="forgot-password">
                <a href="#">Forgot password?</a>
            </div>
            <button type="submit" class="btn">Login</button>
        </form>
        <div class="social-login">
            <p>Or Login In Using</p>
            <div class="icons">
                <a href="#" class="facebook">F</a>
                <a href="#" class="google">G</a>
            </div>
            <p class="signup">Don't have an account? <a href="SIGN.HTML" target="_blank">Sign Up</a></p>
        </div>
    </div>
</body>
</html>

```
Sign in page.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign In</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #11998e, #38ef7d); /* Changed background */
            color: #fff;
        }
        .container {
            background: #ffffff;
            color: #000;
            border-radius: 10px;
            padding: 35px;
            width: 400px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        h2 {
            margin-bottom: 20px;
        }
        form {
            text-align: left;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            font-size: 14px;
            margin-bottom: 5px;
        }
        .form-group input {
            width: 100%;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .btn {
            background: linear-gradient(135deg, #11998e, #38ef7d); /* Matching new color */
            border: none;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            width: 100%;
            cursor: pointer;
            font-size: 16px;
        }
        .social-login {
            margin-top: 20px;
        }
        .social-login p {
            font-size: 14px;
            margin-bottom: 10px;
        }
        .social-login .icons {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .social-login .icons a {
            text-decoration: none;
            color: #fff;
            font-size: 18px;
            width: 30px;
            height: 30px;
            line-height: 30px;
            border-radius: 50%;
            text-align: center;
        }
        .social-login .icons .facebook {
            background-color: #4267b2;
        }
        .social-login .icons .google {
            background-color: #db4437;
        }
        .signup {
            font-size: 14px;
            margin-top: 10px;
        }
        .signup a {
            text-decoration: none;
            color: #007bff;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Sign In</h2>
        <form action="#">
            <div class="form-group">
                <label for="first-name">First Name</label>
                <input type="text" id="first-name" placeholder="Type your first name" required>
            </div>
            <div class="form-group">
                <label for="last-name">Last Name</label>
                <input type="text" id="last-name" placeholder="Type your last name" required>
            </div>
            <div class="form-group">
                <label for="email">Mail-Id</label>
                <input type="email" id="email" placeholder="Type your email" required>
            </div>
            <div class="form-group">
                <label for="mobile">Mobile Number</label>
                <input type="tel" id="mobile" placeholder="Type your mobile number" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" placeholder="Type your password" required>
            </div>
            <button type="submit" class="btn">Sign In</button>
        </form>
        <div class="social-login">
            <p>Or Sign Up Using</p>
            <div class="icons">
                <a href="#" class="facebook">F</a>
                <a href="#" class="google">G</a>
            </div>
        </div>
    </div>
</body>
</html>

```
# OUTPUT:
![screencapture-file-C-Users-admin-OneDrive-Desktop-DRIBBLE-Dribbble-page-html-2025-05-19-21_37_38](https://github.com/user-attachments/assets/e1380fd0-b8e3-4712-9987-d3f4132c9277)
![Screenshot 2025-05-19 205847](https://github.com/user-attachments/assets/c39255c6-8d34-4925-8217-0cef5610aa3c)
![Screenshot 2025-05-19 210335](https://github.com/user-attachments/assets/819e7274-ec1a-44fe-9063-d9b5f6adf67d)



# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
