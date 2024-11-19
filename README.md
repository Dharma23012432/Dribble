Project Responsive Web Design using Bootstrap
## Date: 19.11.2024

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
## index.html :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                    <li class="nav-item"><a class="btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <section class="py-4 text-center bg-light">
        <div class="container">
            <h1 class="display-5">What are you working on?</h1>
            <p class="lead">Dribbble is a show-and-tell platform for designers.</p>
            <a href="#" class="btn btn-primary">Learn More</a>
        </div>
    </section>
    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="mb-0">Popular</h2>
                </div>
                <div class="col-md-8 text-end">
                    <button class="btn btn-light btn-sm">Now</button>
                    <button class="btn btn-light btn-sm">Shots</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/userupload/12044924/file/original-7441c7cdad59beb6ce7a7aab319110b9.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 1">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">By Famous</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/userupload/15653410/file/original-bbeafec513b47d157ad760114cd9adb5.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">San Brothers</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/users/40433/screenshots/2928289/media/a231b5daaa0520ad061991eeb51751dc.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Ueno</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/userupload/8483051/file/still-acd7ce3861ca63447f9f5d496cb494e5.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Awe Design Studio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/users/140043/screenshots/9106916/dribbble_4_compressed.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">MakeReign</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/users/6061337/screenshots/15342859/media/fe77d53ece15bbffb04f175ded73c900.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">heartbeat</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/users/1739084/screenshots/4448965/kyzzlj.jpg?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Wkio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/userupload/10964296/file/original-ffa83431e0b8639f6d1036a0f80c76ae.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Looksgreat</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer class="bg-light py-3">
        <div class="container text-center">
            <p class="mb-0">&copy; 2024 Dribbble Clone. All rights reserved.</p>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
```
## style.css:
```/* General Styles */
body {
    background-color: #f8f9fa;
    font-family: Arial, Helvetica, sans-serif;
}

/* Navbar */
.navbar-brand {
    font-weight: bold;
    color: #ff5678 !important;
}

.nav-link {
    color: #333 !important;
    margin-right: 15px;
}

.nav-link.btn {
    padding: 8px 16px;
    font-size: 0.9rem;
}

/* Hero Section */
.hero-section h1 {
    font-size: 2.5rem;
    color: #333;
}

.hero-section p {
    font-size: 1.2rem;
    margin-bottom: 20px;
    color: #666;
}

/* Shot Cards */
.shot-card img {
    border-radius: 5px;
}

.shot-card {
    transition: transform 0.2s ease-in-out;
}

.shot-card:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

/* Footer */
footer {
    background-color: #ffffff;
    color: #333;
    padding: 20px 0;
    text-align: center;
}

```
## acript.js :
```
// Add a smooth scroll effect for navigation links
document.querySelectorAll(".nav-link").forEach(link => {
    link.addEventListener("click", event => {
        event.preventDefault();
        const targetId = link.getAttribute("href").replace("#", "");
        const targetElement = document.getElementById(targetId);
        if (targetElement) {
            window.scrollTo({
                top: targetElement.offsetTop,
                behavior: "smooth"
            });
        }
    });
});
```

## OUTPUT:
![Screenshot 2024-11-19 122151](https://github.com/user-attachments/assets/c82b74dd-68b7-4ee0-82da-f527881d3022)
![Screenshot 2024-11-19 122210](https://github.com/user-attachments/assets/b67bd5ac-6320-42d8-85e6-7e319f07688a)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
