# Ex.07 Restaurant Website
# Date:06.10.25
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
sample.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vitchu Restaurant</title>
 <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Open Sans', sans-serif;
    }

    body {
      background-color: #fafaf9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #fbde05;
      text-align: center;
      padding: 7px 0;
     
    }

   

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5em;
      color: #502e2c;
      margin-top: 7px;
    }

    nav {
      background-color:  #0a0a0a;
      display: flex;
      justify-content: center;
      gap: 7px;
      padding: 7px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 5px 15px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    

    .hero {
      background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 7px 7px;
      border-radius: 8px;
      margin: 7px auto;
      max-width: 1000px;
    }

    .hero h2 {
      font-size: 3em;
      font-family: 'Playfair Display', serif;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 700px;
      margin: auto;
      font-size: 1.2em;
      background-color: rgba(0, 0, 0, 0.5);
      padding: 5px;
      border-radius: 8px;
      line-height: 1.8;
    }

    .sections {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin: 10px auto;
      max-width: 1000px;
      gap: 20px;
    }

    .section {
      background-color: #fff;
      border-radius: 20px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      flex: 1;
      min-width: 280px;
      padding: 10px;
      transition: transform 0.3s;
    }

    .section:hover {
      transform: translateY(-5px);
    }

    .section h3 {
      font-family: 'Playfair Display', serif;
      color: #f61e1e;
      margin-bottom: 5px;
    }

    .section img {
      width: 100%;
      height: 180px;
      border-radius: 8px;
      object-fit: cover;
      margin-bottom: 5px;
    }

    footer {
      text-align: center;
      padding: 50px;
      background-color: #ebeb09;
      color: white;
      margin-top: 20px;
    }
    .logo-title {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 7px;
}

.logo-title img {
  height: 50px;
}

.logo-title h1 {
  font-family: 'Playfair Display', serif;
  font-size: 2.5em;
  color: #970909;
  margin: 0;
}

  </style>
</head>
<body>

<header>
  <div class="logo-title">
    <img src="https://thumbs.dreamstime.com/z/restaurant-logo-letter-v-concept-letter-v-logo-chef-hat-spoon-fork-restaurant-logo-letter-v-concept-letter-v-logo-263450848.jpg" alt="VITCHU RESTAURANT" />
    <h1>VITCHU RESTAURANT</h1>
    <img src="https://tse4.mm.bing.net/th/id/OIP.75_EhzrXvLCJUv-wA0mwxQHaFz?cb=12&rs=1&pid=ImgDetMain&o=7&rm=3">
  </div>
</header>


  <nav>
   
    <a href="food.html">Menu</a>
    <a href="trial.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="hero">
    <h2>25% Off This Weekend</h2>
    <p>
      Serving bold flavors and fresh ingredients.<br>
      We're your go-to spot for great eats and good vibes.<br>
      Locally loved, globally inspired.<br>
      Welcome to food that feels like home.
    </p>
  </section>

  <div class="sections">

    <div class="section">
      <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=600&q=80" alt="New Menu">
      <h3>Our New Menu</h3>
      <p>Explore delicious new dishes added by our chefs. Fresh, seasonal, and full of flavor!</p>
    </div>

    <div class="section">
      <img src="https://images.unsplash.com/photo-1528605248644-14dd04022da1?auto=format&fit=crop&w=600&q=80" alt="Book a Table">
      <h3>Book a Table</h3>
      <p>Reserve your favorite spot online in just a few clicks. We're excited to serve you!</p>
    </div>

    <div class="section">
      <img src="https://images.unsplash.com/photo-1498654896293-37aacf113fd9?auto=format&fit=crop&w=600&q=80" alt="Opening Hours">
      <h3>Opening Hours</h3>
      <p>Mon - Fri: 10am - 10pm<br>Sat - Sun: 9am - 11pm</p>
    </div>

  </div>
<footer style="display: flex; justify-content: space-between; align-items: center; padding: 10px; background-color: #050505; color: white; margin-top: 50px; max-width: 10000px; margin-left:auto; margin-right:auto;">
  <div></div> 
  <div style="text-align:center;">&copy; 2025 Vitchu Restaurant. All Rights Reserved.</div>
  <div style="text-align:right;">Created by Ishwarya.M</div>
</footer>


</body>
</html> 





food.html

<!DOCTYPE html>
<html>
<head>
  <title>Food Menu</title>
</head>
<body style="font-family: Arial; background-color: #fdfd05; text-align: center;">
 <style>
    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    </style>
  <h1>🍔 Food Menu 🍕</h1>
 <nav>
    <a href="sample.html">Home</a>
    <a href="contact.html">Contact</a>
    
    <a href="trial.html">Administrator</a>
  </nav>
  <h2>Starters</h2>
  <p>Veg Soup - ₹80</p>
  <p>Paneer Tikka - ₹120</p>

  <h2>Main Course</h2>
  <p>Veg Fried Rice - ₹130</p>
  <p>Butter Chicken - ₹220</p>

  <h2>Desserts</h2>
  <p>Ice Cream - ₹70</p>
  <p>Gulab Jamun - ₹60</p>

</body>
</html>





contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff8f0;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #f60303;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .container {
      width: 90%;
      max-width: 600px;
      margin: 30px auto;
      background-color: white;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    h2 {
      text-align: center;
      color: #f60303;
    }
    label {
      display: block;
      margin-top: 15px;
      color: #333;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      display: block;
      width: 100%;
      background-color: #f60303;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      margin-top: 15px;
      cursor: pointer;
    }
    button:hover {
      background-color: #e5533c;
    }
    .info {
      margin-top: 20px;
      text-align: center;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Vitchu Restaurant's Foodies</h1>
    <p>We'd love to hear from you!</p>
  </header>
<nav>
    <a href="sample.html">Home</a>
    <a href="food.html">Menu</a>
    
    <a href="trial.html">Administrator</a>
  </nav>
  <div class="container">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Your Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required>

      <label for="email">Your Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required>

      <label for="message">Your Message:</label>
      <textarea id="message" name="message" rows="4" placeholder="Write your message..." required></textarea>

      <button type="submit">Send Message</button>
    </form>

    <div class="info">
      <p>📍 123 Food Street, Chennai</p>
      <p>📞 +91 98765 43210</p>
      <p>✉ contact@vitchurestaurant.com</p>
      <p>Open: Mon–Sun, 10 AM – 11 PM</p>
    </div>
  </div>
</body>
</html>




trial.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Admin Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
    header {
      background: #48f7f7;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .team-section {
      background: #f2f2f2;
      padding: 30px;
      text-align: center;
    }
    .team-title {
      font-size: 24px;
      margin-bottom: 20px;
    }
    .team-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }
    .member {
      background: white;
      border-radius: 15px;
      padding: 20px;
      width: 150px;
      box-shadow: 0px 4px 6px rgba(0,0,0,0.2);
    }
    .member img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
    }
    .member h4 {
      margin: 10px 0 5px;
    }
    .member p {
      margin: 0;
      font-size: 14px;
      color: gray;
    }
   
  </style>
</head>
<body>

  <header>
    <h1>Restaurant Admin Page</h1>
  </header>

  <nav>
    <a href="sample.html">Home</a>
    <a href="food.html">Menu</a>
    
    <a href="contact.html">Contact</a>
  </nav>

  <section class="team-section">
    <h2 class="team-title">Our Restaurant Team</h2>
    <div class="team-container">
      <div class="member">
        <img src="c:\Users\acer\Downloads\IMG_20250906_210826.jpg" alt="CEO">
        <h4>Ishwarya M</h4>
        <p>CEO</p>
      </div>
      <div class="member">
        <img src="https://i.pinimg.com/736x/cf/c6/4d/cfc64d0c8c3b9440f679ac1ab81e99f1.jpg" alt="Co-CEO">
    <h4>Thalapathy Vijay</h4>
<p>Co-CEO</p></div>
      <div class="member">
        <img src="c:\Users\acer\Downloads\Snapchat-1353220846.jpg" alt="Chef">
        <h4>Vishnu Priya M</h4>
        <p>Head Chef</p>
      </div>
      
      
      <div class="member">
        <img src="c:\Users\acer\Downloads\Screenshot_20251006_214259.jpg" alt="Staff">
        <h4>Balaji M</h4>
        <p>Waiter</p>
      </div>
      <div class="member">
        <img src="c:\Users\acer\Downloads\Snapchat-2081373170.jpg" alt="Staff">
        <h4>Kalpana M</h4>
        <p>Cashier</p>
      </div>
    </div>
  </section>

  

</body>
</html>
```
# OUTPUT:
![alt text](<restaurant/foodapp/static/Screenshot (41).png>)
![alt text](<restaurant/foodapp/static/Screenshot (42).png>)
![alt text](<restaurant/foodapp/static/Screenshot (44).png>)
![alt text](<restaurant/foodapp/static/Screenshot (45).png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
