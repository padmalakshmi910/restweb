# Ex.07 Restaurant Website
## Date:30.09.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
administration.html
<!DOCTYPE html>
<html>
<head>
  <title>Administration</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="admin-page">

<header>
  <h1>Our Team</h1>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>

<div class="admin-container">
  
  <div class="admin-card"><img src="admin1.jpg"><h3>John Smith</h3><p>Manager</p></div>
  <div class="admin-card"><img src="admin2.jpg"><h3>Jane Doe</h3><p>Head Chef</p></div>
  <div class="admin-card"><img src="admin3.jpg"><h3>Mike Johnson</h3><p>Marketing</p></div>
  <div class="admin-card"><img src="admin4.jpg"><h3>Sara Lee</h3><p>Accountant</p></div>
  <div class="admin-card"><img src="admin5.jpg"><h3>Tom Clark</h3><p>Operations</p></div>
  <div class="admin-card"><img src="admin6.jpg"><h3>Nina Patel</h3><p>Support</p></div>
</div>


<footer class="site-footer">
  <div class="footer-left">Designed by <strong>PADMA LAKSHMI G</strong></div>
  <div class="footer-right">© 2025 ELITE</div>
</footer>

</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - ELITE</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="contact-page">


<header class="site-header">
  <h1>Contact Us</h1>
</header>

<nav class="navbar">
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>

<section class="contact-section">
  <h2>We're Here to Help</h2>
  <p><strong>Address:</strong> 123 Lemon Street, Flavor Town, USA</p>
  <p><strong>Phone:</strong> +1 (555) 123-4567</p>
  <p><strong>Email:</strong> contact@elitepremium.com</p>
</section>

<footer class="site-footer">
  <div class="footer-left">Designed by <strong>PADMA LAKSHMI G</strong></div>
  <div class="footer-right">© 2025 ELITE</div>
</footer>


</body>
</html>

index.html
<!DOCTYPE html>
<html>
<head>
  <title>Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="index-page">

<header class="site-header">
  <div class="logo">
    <img src="logo.jpg" alt="ELITE Logo">
    <h1>ELITE</h1>
  </div>
</header>


<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>


<section class="banner">
  <div class="banner-overlay">
    <h2>30% Off This Weekend</h2>
    <p>Delicious food awaits you Visit us today!</p>
  </div>
</section>


<footer class="site-footer">
  <div class="footer-left">Designed by <strong>PADMA LAKSHMI G</strong></div>
  <div class="footer-right">© 2025 ELITE</div>
</footer>

</body>
</html>

menu.html
<!DOCTYPE html>
<html>
<head>
  <title>Menu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="menu-page">

<header>
  <h1>Our Menu</h1>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>

<div class="main-gallery">
  <!-- 12 Food Items -->
   <div class="photo-grid">
  <div class="menu-item"><img src="food1.jpg"><h3>Pizza</h3><p>$10.00</p></div>
  <div class="menu-item"><img src="food2.jpg"><h3>Burger</h3><p>$7.00</p></div>
  <div class="menu-item"><img src="food3.jpg"><h3>Pasta</h3><p>$8.00</p></div>
  <div class="menu-item"><img src="food4.jpg"><h3>Sushi</h3><p>$12.00</p></div>
  <div class="menu-item"><img src="food5.jpg"><h3>Salad</h3><p>$6.00</p></div>
  <div class="menu-item"><img src="food6.jpg"><h3>Steak</h3><p>$15.00</p></div>
  <div class="menu-item"><img src="food7.jpg"><h3>Tacos</h3><p>$5.00</p></div>
  <div class="menu-item"><img src="food8.jpg"><h3>Fries</h3><p>$3.00</p></div>
  <div class="menu-item"><img src="food9.jpg"><h3>Wrap</h3><p>$6.50</p></div>
  <div class="menu-item"><img src="food10.jpg"><h3>Sandwich</h3><p>$4.50</p></div>
  <div class="menu-item"><img src="food11.jpg"><h3>Ice Cream</h3><p>$2.50</p></div>
  <div class="menu-item"><img src="food12.jpg"><h3>Milkshake</h3><p>$3.50</p></div>
</div>
</div>
<footer class="site-footer">
  <div class="footer-left">Designed by <strong>PADMA LAKSHMI G</strong></div>
  <div class="footer-right">© 2025 ELITE</div>
</footer>


</body>
</html>

styles.css
/* ==== RESET & BASE ==== */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* General body styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fff;
  color: #333;
}

/* Headings */
h1 {
  text-align: center;  /* Center all h1 headings */
  font-size: 36px;
  color: #181716;
  font-weight: 700;
  margin: 40px 0 20px 0;
  letter-spacing: 2px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body.index-page {
  background: linear-gradient(135deg, #d62090, #894275);
  background-attachment: fixed;
  color: #fff;
}

body.menu-page {
  background: radial-gradient(circle at top left, #063342, #406489);
  background-attachment: fixed;
  color: #fff;
}

body.admin-page {
  background: linear-gradient(45deg, #8E2DE2, #4A00E0);
  background-attachment: fixed;
  color: #fff;
}

body.contact-page {
  background: linear-gradient(to right, #43CEA2, #185A9D);
  background-attachment: fixed;
  color: #fff;
}


img {
  max-width: 100%;
  display: block;
}

/* ==== HEADER & LOGO ==== */
.site-header {
  background-color: #ffffff;
  padding: 30px 0;
  text-align: center;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 16px;
}

.logo img {
  width: 70px;
  height: auto;
}

.logo h1 {
  font-size: 38px;
  font-family: 'Georgia', serif;
  color: #2c3e50;
}

nav {
  background-color: #FF6F00; /* your banner color */
  padding: 20px 0;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: inline-flex;
  gap: 50px;              /* more spacing between items */
}

nav ul li a {
  color: white;           /* white text */
  text-decoration: none;
  font-size: 28px;        /* bigger font size */
  font-weight: 700;
  padding: 10px 20px;
  border-radius: 8px;
  transition: background-color 0.3s;
}

nav ul li a:hover,
nav ul li a.active {
  background-color: #e65c00;  /* darker orange on hover */
  color: white;
}


/* ==== BIGGER BANNER FOR HOME ONLY ==== */
.banner {
  position: relative;
  background: url('banner.jpg') no-repeat center center/cover;
  height: 500px; /* Bigger banner */
  margin: 40px auto;
  border-radius: 16px;
  width: 95%;
  max-width: 1400px;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.25);
  display: flex;
  align-items: center;
  justify-content: center;
}

.banner-overlay {
  background-color: rgba(0, 0, 0, 0.55);
  color: white;
  padding: 60px 80px;
  border-radius: 16px;
  text-align: center;
  max-width: 90%;
}

.banner-overlay h2 {
  font-size: 54px;
  margin-bottom: 20px;
  font-family: 'Georgia', serif;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.4);
}

.banner-overlay p {
  font-size: 24px;
  text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.3);
}

/* ==== FEATURES (HOME ONLY, LARGER) ==== */
.features {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 40px;
  padding: 60px 40px;
  max-width: 1400px;
  margin: auto;
}

.feature-card {
  background-color: #fcebd5;
  width: 320px;
  padding: 25px;
  border-radius: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
}

.feature-card img {
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 15px;
}

.feature-card h3 {
  color: #FF6F00;
  font-size: 22px;
  margin-bottom: 10px;
}

.menu-heading {
  text-align: center;          /* center text horizontally */
  font-size: 36px;             /* adjust size as needed */
  color: #FF6F00;              /* your theme color */
  font-weight: 700;
  margin: 40px 0 20px 0;
  letter-spacing: 2px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}


.menu-fullscreen {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  height: 100vh;
  max-width: 1400px;
  margin: auto;
  padding: 20px;
  gap: 36px;           /* a bit more space for bigger photos */
  box-sizing: border-box;
  overflow: hidden;
  position: relative;
}

/* Reset & basics */
* {
  box-sizing: border-box;
}

/* ==== RESET & BASE ==== */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* General body styles */
body {
  font-family: Arial, sans-serif;
  background-color: #fff;
  color: #333;
  height: 100vh;
  overflow: hidden; /* Prevent scrolling */
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  padding: 20px;
}

/* Headings */
h1 {
  font-size: 36px;
  color: #c2bbb5;
  font-weight: 700;
  letter-spacing: 2px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin-bottom: 30px;
  text-align: center;
  width: 100%;
  max-width: 960px;
}

/* Container for photos */
.photo-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr); /* 4 columns */
  grid-template-rows: repeat(3, 1fr);    /* 3 rows */
  gap: 20px;
  width: 100%;
  max-width: 960px;
  height: calc(100vh - 180px); /* Viewport minus heading and footer approx */
  max-height: 720px;
  overflow: hidden;
  justify-items: center;
  align-items: center;
}

/* Photos style */
.photo-grid img {
  width: 140px;
  height: 140px;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.25);
  cursor: pointer;
  transition: transform 0.3s ease;
  user-select: none;
}

.photo-grid img:hover {
  transform: scale(1.1);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.5);
}

/* Footer below photos */
.site-footer {
  margin-top: 30px;
  width: 100%;
  max-width: 960px;
  background-color: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
  font-size: 14px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.site-footer strong {
  font-size: 18px;
  color: #FF6F00;
  display: block;
  margin-bottom: 8px;
}

.footer-left,
.footer-right {
  margin: 4px 0;
  color: #ccc;
  font-weight: 600;
  letter-spacing: 0.5px;
}

/* Responsive */
@media (max-width: 700px) {
  .photo-grid {
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(4, 1fr);
    max-height: 720px;
  }

  .photo-grid img {
    width: 110px;
    height: 110px;
  }

  .site-footer {
    font-size: 12px;
  }
}

.menu-item {
  flex: 0 0 180px;     /* fixed width so they don’t shrink */
  text-align: center;
  position: relative;
}

.menu-item img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.25);
  margin-bottom: 14px;
  transition: transform 0.3s;
  cursor: pointer;
}

.menu-item img:hover {
  transform: scale(1.1);
}

.menu-item h3 {
  font-size: 17px;
  color: #FF6F00;
  margin: 0;
  font-weight: 600;
}

/* Slight random vertical offsets for scattered effect */
.menu-item:nth-child(3n) {
  margin-top: 24px;
}

.menu-item:nth-child(4n) {
  margin-bottom: 24px;
}

.admin-container {
  display: flex;
  flex-wrap: nowrap;           /* no wrap, force horizontal */
  justify-content: space-around; /* spread evenly */
  align-items: center;
  height: 100vh;               /* full viewport height */
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  box-sizing: border-box;
  overflow-x: auto;            /* horizontal scroll if very narrow screens */
  background-color: #fff8f0;   /* soft warm background */
}

/* Individual admin card */
.admin-heading {
  text-align: center;          /* center text horizontally */
  font-size: 36px;             /* adjust size as needed */
  color: #FF6F00;              /* your theme color */
  font-weight: 700;
  margin: 40px 0 20px 0;
  letter-spacing: 2px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.admin-card {
  background-color: #fff;
  border-radius: 15px;
  width: 180px;
  min-width: 180px;
  padding: 20px;
  box-shadow: 0 8px 16px rgba(255, 111, 0, 0.3);
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: default;
}

/* Hover effect */
.admin-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 12px 25px rgba(255, 111, 0, 0.5);
}

/* --- Existing styles above --- */

/* Administration photos */
.admin-card img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  transition: transform 0.3s ease;
}

.admin-card img:hover {
  transform: scale(1.05);
}


/* Admin name */
.admin-card h3 {
  font-size: 20px;
  color: #964c4c;
  margin: 10px 0 6px 0;
  font-weight: 700;
}

/* Designation */
.admin-card p {
  font-size: 16px;
  color: #666;
  margin: 0;
  font-style: italic;
}


/* ==== CONTACT PAGE ==== */
.contact-section {
  background-color: #96682c;
  max-width: 700px;
  margin: 60px auto;
  padding: 40px;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
}

.contact-section h2 {
  font-size: 26px;
  margin-bottom: 20px;
  color: #0c0c0c;
}

.contact-section p {
  font-size: 18px;
  margin: 10px 0;
}

/* ==== FOOTER ==== */
.site-footer {
  background-color: #333;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 60px;
  font-size: 15px;
  margin-top: 60px;
}

.site-footer strong {
  font-size: 18px;
  color: #FF6F00;
}

.footer-left {
  text-align: left;
}

.footer-right {
  text-align: right;
}

~~~
## OUTPUT:
![alt text](<Screenshot 2025-09-30 121230.png>)
![alt text](<Screenshot 2025-09-30 113647.png>)
![alt text](<Screenshot 2025-09-30 113703.png>)
![alt text](<Screenshot 2025-09-30 113724.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
