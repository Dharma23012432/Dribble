# Project Responsive Web Design using Bootstrap
## Date:

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
    <title>Design Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Top Navigation Bar -->
    <div class="top-bar">
        <input type="text" class="search-bar" placeholder="Search...">
        <a href="#" class="nav-item">Explore</a>
        <a href="#" class="nav-item">Hire a Designer</a>
        <a href="#" class="nav-item">Find Jobs</a>
        <a href="#" class="nav-item">Blog</a>
        <a href="#" class="nav-item blue-text">Sign up</a>
        <a href="#" class="nav-item blue-text">Log in</a>
    </div>

    <!-- Header Section -->
    <header>
        <div class="header-content">
            <h1>Discover the world’s top designers</h1>
            <p>Explore work from the most talented and accomplished designers ready to take on your next project</p>
            <input type="text" class="search-input" placeholder="What are you looking for?">
        </div>
    </header>

    <!-- Trending Searches Section -->
    <section class="trending">
        <h2>Trending Searches</h2>
        <div class="trending-tags">
            <span>landing page</span>
            <span>e-commerce</span>
            <span>mobile app</span>
            <span>logo design</span>
            <span>dashboard</span>
            <span>icons</span>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery">

        <div class="card">
            <img src="https://images.pexels.com/photos/11760851/pexels-photo-11760851.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Design Sample">
            <h3>Elephant</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/4749959/pexels-photo-4749959.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Ducks</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/326012/pexels-photo-326012.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Design Sample">
            <h3>Rabbit</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/4654630/pexels-photo-4654630.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Deer</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/1319515/pexels-photo-1319515.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Whale</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/4666751/pexels-photo-4666751.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Whale</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/1321524/pexels-photo-1321524.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Butterfly</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/3608263/pexels-photo-3608263.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Panda</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/160722/cat-tiger-getiegert-feel-at-home-160722.jpeg" alt="Design Sample">
            <h3>Cat</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/2832217/pexels-photo-2832217.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>squirrel</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/598966/pexels-photo-598966.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Design Sample">
            <h3>Beer</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/792381/pexels-photo-792381.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Design Sample">
            <h3>Tiger</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>
        <!-- Add more cards as needed -->
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Design Portfolio. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```
## style.css:
```
/* Reset and basic styles */
body, h1, h2, p, a, input, button {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #333;
}

/* Top Bar Styling */
.top-bar {
    display: flex;
    align-items: center;
    background-color: #ffffff;
    padding: 10px 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.search-bar {
    margin-right: 15px;
    padding: 8px;
    border: 1px solid #ddd;
    border-radius: 4px;
    outline: none;
}

.nav-item {
    margin: 0 10px;
    color: #333;
    text-decoration: none;
}

.blue-text {
    color: #007bff;
    font-weight: bold;
}

.blue-text:hover {
    text-decoration: underline;
}

/* Header Section */
header {
    background-image: url('https://images.pexels.com/photos/1072179/pexels-photo-1072179.jpeg'); /* Add your header image */
    background-size: cover;
    padding: 80px 20px;
    text-align: center;
    color: #fff;
}

.header-content h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.header-content p {
    font-size: 18px;
    margin-bottom: 20px;
}

.search-input {
    padding: 10px;
    width: 60%;
    max-width: 500px;
    border: none;
    border-radius: 4px;
    outline: none;
}

/* Trending Searches Section */
.trending {
    padding: 20px;
    text-align: center;
}

.trending h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

.trending-tags {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.trending-tags span {
    background-color: #007bff;
    color: #fff;
    padding: 5px 10px;
    margin: 5px;
    border-radius: 4px;
    font-size: 14px;
}

/* Gallery Section */
.gallery {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
}

.card img {
    width: 100%;
    height: auto;
}

.card h3 {
    font-size: 16px;
    margin: 10px 0;
}

.card p {
    font-size: 12px;
    color: #555;
    margin-bottom: 10px;
}

/* Gallery Section */
.gallery {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
    position: relative;
}

.card img {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease;
}

.card:hover img {
    transform: scale(1.2); /* Scale image to 120% on hover */
}

.card h3 {
    font-size: 16px;
    margin: 10px 0;
}

.card p {
    font-size: 12px;
    color: #555;
    margin-bottom: 10px;
}

/* Footer Section */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 20px;
    margin-top: 20px;
}
```
## acript.js :
```
// Search functionality
const searchBar = document.querySelector('.search-bar');

searchBar.addEventListener('keydown', function(event) {
    if (event.key === 'Enter') {
        event.preventDefault(); // Prevent default form submission
        alert(`Searching for: ${searchBar.value}`);
    }
});
```

## OUTPUT:
![Screenshot 2024-11-19 102459](https://github.com/user-attachments/assets/3896190d-6918-4ac6-a540-2e62df06ca17)
![Screenshot 2024-11-19 102508](https://github.com/user-attachments/assets/ca7ca54b-6d14-4327-9bdd-575b93771781)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
