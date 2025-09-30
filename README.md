# StaticWebHub on GitHub

# MyWebsite
---
```
MyWebsite/
│
├── index.html
├── about.html
├── contact.html
├── style.css
└── images/ ←  folder for images like logos, banners, etc.
```

### Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <!-- Logo -->
        <img src="images/logo.png" alt="MyWebsite Logo" style="width:120px; display:block; margin: 0 auto 20px;">
        
        <nav>
            <ul>
                <li><a href="index.html" class="active">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <h1>Welcome to My Professional Website</h1>
        <p>Hosted on GitHub Pages</p>

        <!-- Banner Image -->
        <img src="images/banner.jpg" alt="Website Banner" style="width:100%; max-height:300px; object-fit:cover; margin-top:20px;">
    </header>
    <main>
        <section>
            <h2>Our Services</h2>
            <p>We provide clean and professional static websites using GitHub Pages.</p>
        </section>
        <section>
            <h2>Get Started</h2>
            <p>Customize your website with HTML, CSS, and JavaScript.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 MyWebsite. All rights reserved.</p>
    </footer>
</body>
</html>
```
### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - My Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <!-- Logo -->
        <img src="images/logo.png" alt="MyWebsite Logo" style="width:100px; display:block; margin: 0 auto 20px;">
        
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html" class="active">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <h1>About Us</h1>

        <!-- Profile Image -->
        <img src="images/profile.png" alt="Team Profile" style="width:150px; border-radius:50%; display:block; margin: 20px auto;">
    </header>
    <main>
        <section>
            <h2>Our Mission</h2>
            <p>We aim to simplify static website deployment with GitHub Pages.</p>
        </section>
        <section>
            <h2>Our Vision</h2>
            <p>To make professional websites accessible to everyone for free.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 MyWebsite. All rights reserved.</p>
    </footer>
</body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - My Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <!-- Logo -->
        <img src="images/logo.png" alt="MyWebsite Logo" style="width:100px; display:block; margin: 0 auto 20px;">
        
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html" class="active">Contact</a></li>
            </ul>
        </nav>
        <h1>Contact Us</h1>
    </header>
    <main>
        <section>
            <h2>Get in Touch</h2>
            <p>Email: contact@mywebsite.com</p>
            <p>Phone: +91 12345 67890</p>
        </section>
        <section>
            <h2>Follow Us</h2>
            <p>Twitter | LinkedIn | GitHub</p>

            <!-- Banner Image -->
            <img src="images/banner.jpg" alt="Follow Us Banner" style="width:100%; max-height:250px; object-fit:cover; margin-top:20px;">
        </section>
    </main>
    <footer>
        <p>&copy; 2025 MyWebsite. All rights reserved.</p>
    </footer>
</body>
</html>
```
### style.css
```
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f7f9;
    color: #333;
}

/* Header & Navigation */
header {
    background-color: #0077cc;
    color: #fff;
    text-align: center;
    padding: 30px 20px;
}

header img {
    display: block;
    margin: 0 auto 20px;
}

/* Navigation Menu */
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
    transition: background-color 0.3s, color 0.3s;
}

nav ul li a.active, nav ul li a:hover {
    text-decoration: underline;
    background-color: rgba(255, 255, 255, 0.2);
    border-radius: 5px;
}

/* Main Content */
main {
    padding: 20px;
    max-width: 800px;
    margin: 0 auto;
}

main section {
    margin-bottom: 30px;
}

h1, h2 {
    margin: 10px 0;
}

/* Images inside main */
main img {
    max-width: 100%;
    height: auto;
    margin: 20px 0;
    border-radius: 10px;
}

/* Footer */
footer {
    background-color: #222;
    color: #fff;
    text-align: center;
    padding: 15px 0;
}

/* Responsive for small screens */
@media screen and (max-width: 600px) {
    nav ul {
        flex-direction: column;
        gap: 10px;
    }
    header {
        padding: 20px 10px;
    }
}
```
## ✅  Host on GitHub Pages

1. Push project files to a GitHub repository (e.g., `MyWebsite`)
2. Go to  
   **Settings → Pages**
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. GitHub will generate a live site link in below
   [![Live Demo](https://img.shields.io/badge/Website-Live-brightgreen?style=for-the-badge&logo=github)](https://nikhilk814.github.io/StaticWebHub/index.html)





<img width="1817" height="793" alt="pages" src="https://github.com/user-attachments/assets/1afde1ea-89a5-401d-bf3c-472166a79bd0" />
<img width="1827" height="741" alt="website" src="https://github.com/user-attachments/assets/617bb041-5ac1-42ec-98e8-ba3fedce3df9" />
<img width="1843" height="937" alt="hosted" src="https://github.com/user-attachments/assets/9799879f-2dc4-42cc-aa5d-ece37f237c88" />


