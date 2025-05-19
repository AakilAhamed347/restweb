# Ex.07 Restaurant Website
## Date:
20.05.25
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
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Spice Delight | Home</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <nav>
      <h1>Spice Delight</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administrative</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h2>Welcome to <span>Spice Delight</span></h2>
      <p>A Symphony of Spices and Flavors</p>
      <a href="menu.html" class="button">Explore Menu</a>
    </div>
  </section>
  <footer>
    <p>&copy; 2025 Spice Delight. All rights reserved.</p>
  </footer>
</body>
</html>

 menu.html

 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Menu | Spice Delight</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <header>
      <nav>
        <h1>Spice Delight</h1>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="admin.html">Administrative</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </header>

    <section class="menu-section">
      <h2>Our Menu</h2>
      <div class="menu-cards">
        <div class="card">
          <img src="images/chicken noodles.jpg" alt="Chicken noodles" />
          <h3>Chicken noodles</h3>
          <p>Delicious and authentic flavor straight from our chef's kitchen.</p>
        </div>

        <div class="card">
          <img src="images/chicken tikka.jpg" alt="chicken Tikka" />
          <h3>Paneer Tikka</h3>
          <p>Delicious and authentic flavor straight from our chef's kitchen.</p>
        </div>

        <div class="card">
          <img src="images/masala dosa.jpg" alt="Masala Dosa" />
          <h3>Masala Dosa</h3>
          <p>Delicious and authentic flavor straight from our chef's kitchen.</p>
        </div>

        <div class="card">
          <img src="images/biriyani.jpg" alt="Biriyani" />
          <h3>Biryani</h3>
          <p>Fragrant basmati rice cooked with tender meat and spices.</p>
        </div>

        <div class="card">
          <img src="images/pavlova.jpg" alt="pavlova" />
          <h3>pavlova</h3>
          <p>Its a meringue based desert with a crisp crust and soft</p>
        </div>

        <div class="card">
          <img src="images/burger.jpg" alt="Burger" />
          <h3>Burger</h3>
          <p>Juicy patty with fresh veggies, sauces, and cheese in a toasted bun.</p>
        </div>

        <div class="card">
          <img src="images/pizza.jpg" alt="Pizza" />
          <h3>Pizza</h3>
          <p>Cheesy, flavorful pizza loaded with toppings and herbs.</p>
        </div>
      </div>
    </section>

    <footer>
      <p>&copy; 2025 Spice Delight. All rights reserved.</p>
    </footer>
  </div>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Administrative | Spice Delight</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <h1>Spice Delight</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administrative</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="highlight">
    <h3>Our Administrative Team</h3>
    <div class="cards">
      <div class="card">
        <img src="images/person7.jpg" alt="Operations Manager" />
        <h4>Operations Manager</h4>
        <p>Ensures the restaurant runs smoothly and efficiently.</p>
      </div>
      <div class="card">
        <img src="images/person8.jpeg" alt="Head Chef" />
        <h4>Head Chef</h4>
        <p>Leads the kitchen team and creates our signature dishes.</p>
      </div>
      <div class="card">
         <img src="images/person9.jpeg" alt="Customer Relations" />
        <h4>Customer Relations</h4>
        <p>Maintains satisfaction and handles feedback with care.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Spice Delight. All rights reserved.</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Contact Us | Spice Delight</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <h1>Spice Delight</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administrative</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="highlight">
    <h3>Contact Us</h3>
    <div class="cards">
      <div class="card">
        <h4>Phone</h4>
        <p>+91 98765 43210</p>
      </div>
      <div class="card">
        <h4>Email</h4>
        <p>spicedelight@example.com</p>
      </div>
      <div class="card">
        <h4>Visit Us</h4>
        <p>123 Spice Street, Chennai, Tamil Nadu</p>
      </div>
    </div>

    <div class="feedback-form">
      <h3>We’d Love Your Feedback</h3>
      <form action="#" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <textarea name="message" rows="5" placeholder="Your Feedback" required></textarea>
        <button type="submit">Submit Feedback</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Spice Delight. All rights reserved.</p>
  </footer>
</body>
</html>

style.css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(to right, #fff0f5, #f0f0ff);
  color: #333;
}

h1, h2 {
  font-family: 'Great Vibes', cursive;
}

header {
  background: white;
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.2rem 10%;
}

nav h1 {
  font-size: 2rem;
  color: #c0392b;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 2rem;
}

nav ul li a {
  text-decoration: none;
  color: #c0392b;
  font-weight: bold;
  position: relative;
  padding-bottom: 4px;
}

nav ul li a::after {
  content: '';
  position: absolute;
  width: 0;
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #c0392b;
  transition: width 0.3s;
}

nav ul li a:hover::after {
  width: 100%;
}

/* Hero Section */
.hero {
  height: 90vh;
  background: url('images/restaurant.jpg') center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
  position: relative;
}

.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.5);
}

.hero-text {
  position: relative;
  z-index: 1;
  max-width: 700px;
}

.hero-text h2 {
  font-size: 3.5rem;
  margin-bottom: 1rem;
}

.hero-text span {
  color: #ffcc00;
}

.hero-text p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.button {
  background: #ffcc00;
  color: #000;
  padding: 12px 30px;
  border-radius: 25px;
  font-weight: 600;
  text-decoration: none;
  transition: background 0.3s;
}

.button:hover {
  background: #e6b800;
}

.highlight {
  padding: 4rem 10%;
  text-align: center;
}

.highlight h3 {
  font-size: 2.2rem;
  margin-bottom: 3rem;
  color: #c0392b;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  justify-content: center;
}

.card {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(10px);
  padding: 2rem;
  border-radius: 15px;
  width: 280px;
}

.feedback-form {
  max-width: 600px;
  margin: 40px auto 0;
  padding: 20px;
  background-color: #fff;
  border-radius: 12px;
  /* removed box-shadow */
}

.feedback-form h3 {
  text-align: center;
  margin-bottom: 20px;
  font-size: 24px;
  color: #d32f2f;
}

.feedback-form form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.feedback-form input,
.feedback-form textarea {
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 16px;
  font-family: inherit;
}

.feedback-form button {
  padding: 12px;
  background-color: #d32f2f;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  font-size: 16px;
  transition: background 0.3s;
}

.feedback-form button:hover {
  background-color: #b71c1c;
}

/* Footer */
footer {
  background: #c0392b;
  color: white;
  text-align: center;
  padding: 1rem;
}
.menu-section {
  padding: 4rem 10%;
  text-align: center;
}

.menu-section h2 {
  font-size: 2.5rem;
  color: #c0392b;
  margin-bottom: 3rem;
}

.menu-cards {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
}

.card {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(10px);
  padding: 1rem;
  border-radius: 15px;
  width: 280px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 15px 15px 0 0;
  margin-bottom: 1rem;
}

.card h3 {
  margin-bottom: 0.5rem;
  color: #c0392b;
}

.card p {
  font-size: 0.95rem;
  color: #444;
}
~~~


## OUTPUT:
![alt text](<Screenshot 2025-05-20 002956.png>) 
![alt text](<Screenshot 2025-05-20 002804.png>)
![alt text](<Screenshot 2025-05-20 002854.png>) 
![alt text](<Screenshot 2025-05-20 002917.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
