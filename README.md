# Ex02 Commercial Website



## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Commercial Website - Home</title>
  <link rel="stylesheet" href="website.css">
</head>
<body>
  <header>
    <div class="logo">Lumora</div>
    <nav>
      <ul>
        <li><a href="home.html" class="active">Home</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contactus.html">Contact</a></li>
      </ul>
    </nav>
  </header>
<h1 class="heading">Welcome to Lumora </h1>
<br>
<p style="text-align: center;">Please Login to Continue your Shopping!!!</p>
<div class="login-box">
    <label>Username</label>
    <input type="text" name="name" id="name">
    <br>
    <label>Password</label>
    <input type="password" name="password" id="password">
    <br>
    <div style="text-align: center;" class="btn">
  <button type="submit">Login</button>
</div>
</div>
<marquee behaviour="solid" direction="right" style="font-weight: bolder;">Flash 50% Off for new users.</marquee>  
</body>
</html>
```
products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Products - MyBrand</title>
  <link rel="stylesheet" href="website.css">
</head>
<body>
  <header>
    <div class="logo">Lumora</div>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="products.html" class="active">Products</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contactus.html">Contact</a></li>
      </ul>
    </nav>
  </header>
  <section class="products-section">
  <h1 class="products-heading">Shop Our Jewellery</h1>
  <div class="main-box">
  <div class="div"><img src="jewel1.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel7.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel3.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel4.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel5.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel6.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel2.jpg"><button class="buy-btn">Buy Now</button></div>
  <div class="div"><img src="jewel8.jpg"><button class="buy-btn">Buy Now</button></div>
  </div>
  </section>

  
</body>
</html>
```
about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Us - MyBrand</title>
  <link rel="stylesheet" href="website.css">
</head>
<body>
  <header>
    <div class="logo">Lumora</div>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="about.html" class="active">About Us</a></li>
        <li><a href="contactus.html">Contact</a></li>
      </ul>
    </nav>
  </header>
    <main class="about-container">
    <section class="about-intro">
      <h1>About Us</h1>
      <p>
        Welcome to <strong>Lumora</strong> – where quality meets style.  
        We are passionate about bringing you the finest products with a focus on
        innovation, durability, and customer satisfaction.
      </p>
    </section>

    <section class="about-mission">
      <h2>Our Mission</h2>
      <p>
        Our mission is simple – to make your life brighter and easier with
        products you can trust. We believe in blending modern design with
        practical use, ensuring you always get the best value.
      </p>
    </section>

    <section class="about-team">
      <h2>Meet Our Team</h2>
      <div class="team-grid">
        <div class="team-member">
          <img src="aishwarya.jpg" alt="Team Member 1">
          <h3>Aishwarya</h3>
          <p>Founder & CEO</p>
        </div>
        <div class="team-member">
          <img src="deepika.jpg" alt="Team Member 2">
          <h3>Deepika</h3>
          <p>Head of Design</p>
        </div>
        <div class="team-member">
          <img src="priyanka.jpg" alt="Team Member 3">
          <h3>Priyanka</h3>
          <p>Marketing Lead</p>
        </div>
      </div>
    </section>
  </main>

  
</body>
</html>
```
contactus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - MyBrand</title>
  <link rel="stylesheet" href="website.css">
</head>
<body>
  <header>
    <div class="logo">Lumora</div>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contactus.html" class="active">Contact</a></li>
      </ul>
    </nav>
  </header>


  <div>
    <h1 style="text-align: center; margin-top: 30px;" >Contact Us</h1>
    <p style="text-align: center;">We’d love to hear from you! Fill out the form below or reach us through our contact details.</p>
  </div>
  <div class="form">
   <form class="contact-form">
        <label for="name">Your Name</label>
        <input type="text" id="name" placeholder="Enter your name" required>
        <br>

        <label for="email">Your Email</label>
        <input type="email" id="email" placeholder="Enter your email" required>
        <br>
        <label for="message">Message</label>
        <br>
        <textarea id="message" rows="5" placeholder="Type your message..." required></textarea>
        <br>
        <button type="submit">Send Message</button>
      </form>
  </div>
   <div class="contact-info">
        <h2>Get in Touch</h2>
        <p><strong>Email:</strong> support@lumora.com</p>
        <p><strong>Phone:</strong> +91 98765 43210</p>
        <p><strong>Address:</strong> Hyderabad, India</p>
        <div class="social-links">
          <a href="#">Facebook</a> |
          <a href="#">Instagram</a> |
          <a href="#"> Twitter</a>
        </div>
      </div>

</body>
</html>
```
website.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: Arial, sans-serif;
  color: #333;
  line-height: 1.6;
  background-color:lightgray;
}
.heading{
    text-align: center;
    margin-top: 20px;
}
header {
  background: #222;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 30px;
}
header .logo {
  font-size: 24px;
  font-weight: bold;
}
nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s;
}
nav ul li a:hover,
nav ul li a.active {
  color: #f39c12;
}
.login-box{
    border:3px solid black;
    width:300px;
    padding: 20px;
    margin: 50px auto;
    border-radius: 15px;
    background-color:lightgray;

}
.btn{
    padding: 10px;
}
.products-heading{
  text-align: center;
  margin-top: 20px;

}

.main-box {
  display: flex;
  flex-wrap: wrap;          
  justify-content: center;  /* center images inside */
  gap: 20px;
  max-width: 1000px;
  margin: 50px auto;        /* optional: control width */
}
.div {
  flex: 0 0 23%;
}
.div img {
  width: 100%;
  border-radius: 10px;
}
.products-section {
  text-align: center;      /* centers heading */
  margin: 30px auto;
  max-width: 1200px;       /* keeps content centered */
}

.products-section h2 {
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}
.buy-btn {
  display: block;
  margin: 10px auto 0;   /* centers button under image */
  padding: 10px 20px;
  background-color: #333;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
  transition: background 0.3s ease;
}

.buy-btn:hover {
  background-color: #555; /* hover effect */
}

.about-container {
  max-width: 1000px;
  margin: 40px auto;
  padding: 20px;
  background:whitesmoke;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.about-intro h1 {
  font-size: 2.2rem;
  margin-bottom: 10px;
  color: #222;
}

.about-intro p {
  font-size: 1.1rem;
  margin-bottom: 30px;
}

.about-mission h2,
.about-team h2 {
  margin-top: 20px;
  color: #444;
}

.about-mission p {
  font-size: 1rem;
  margin-bottom: 30px;
}

.team-grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
}

.team-member {
  background: #f9f9f9;
  border-radius: 8px;
  text-align: center;
  padding: 15px;
  width: 250px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.team-member img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
  margin-bottom: 10px;
}

.team-member h3 {
  margin: 10px 0 5px;
}

form{
  border:3px solid black;
  justify-content: center;
  width: 300px;
  border-radius: 5px;
   padding: 20px;
   margin: 50px auto;
   background-color:lightgray;

}
.contact-info{
  justify-content: center;
  margin: 50px auto;
  border: 3px solid black;
  width:300px;
  padding: 10px;
  border-radius: 5px;
}
```

## OUTPUT
<img width="1919" height="1005" alt="image" src="https://github.com/user-attachments/assets/e006ba14-c9cb-4e07-a5c6-a9353d4a3555" />

<img width="1882" height="990" alt="image" src="https://github.com/user-attachments/assets/6905cb6d-f195-4028-b134-425cc58f6fb3" />

<img width="1862" height="995" alt="image" src="https://github.com/user-attachments/assets/4a8b69cb-2d97-41fa-89ba-229b38537ff7" />

<img width="1913" height="995" alt="image" src="https://github.com/user-attachments/assets/6c2071c7-4683-49aa-8607-74c324deea37" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
