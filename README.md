# Project Responsive Web Design using Bootstrap
## Date:15.10.2025

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
static
administration.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <!-- Repeat for 6 people -->
    <div class="admin-card">
      <img src="manager.jpg" alt="Admin 1">
      <h3>Ram</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="headchef.jpg" alt="Admin 2">
      <h3>Venkat</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="assistantchef.jpg" alt="Admin 3">
      <h3>Rosy</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="cashier.jpg" alt="Admin 4">
      <h3>Sarlett</h3>
      <p>Cashier</p>
    </div>
    <div class="admin-card">
      <img src="inventorymanager.jpg" alt="Admin 5">
      <h3>marie</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="customerservice.jpg"Admin 6">
      <h3>Ravi</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Kabbilesh</p>
  </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 1/5 bazaar road,Anna Nagar,Chennai 37</p>
    <p>📞 <strong>Phone:</strong> 9080583388</p>
    <p>✉ <strong>Email:</strong> durgakanish2407@gmail.com</p>
  </section>

  <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by Kabbilesh</p>
  </footer>

</body>
</html>

index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Cassandra</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Cassandra
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="cassandra"></section>
    <img src="cassandra.jpg"Delicious Food Banner">
  </section>

  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Your Kabbilesh</p>
  </footer>
</body>
</html>

index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="menu-item">
      <img src="pizza.jpg" alt="Pizza">
      <h3>Cheese Pizza</h3>
      <p>Classic cheese pizza with tomato sauce.</p>
    </div>
    <div class="menu-item">
      <img src="burger.jpg" alt="Burger">
      <h3>paneer Burger</h3>
      <p>Grilled paneer patty with fresh veggies.</p>
    </div>
    <div class="menu-item">
      <img src="pasta.jpg" alt="Pasta">
      <h3>Spaghetti Carbonara</h3>
      <p>Rich and creamy with bacon.</p>
    </div>
    <div class="menu-item">
      <img src="salad.jpg" alt="Salad">
      <h3>Caesar Salad</h3>
      <p>Crisp lettuce with creamy Caesar dressing.</p>
    </div>
    <div class="menu-item">
      <img src="sushi.jpg" alt="Sushi">
      <h3>Sushi Rolls</h3>
      <p>Fresh and delicious sushi assortment.</p>
    </div>
    <div class="menu-item">
      <img src="milkshake.jpg" alt="milkshake>
      <h3>chocolate milkshake</h3>
      <p>thick and rich.</p>
    </div>
    <div class="menu-item">
      <img src="french fries.jpg" alt="french fries">
      <h3>french fries</h3>
      <p>Spicy and Crisp</p>
    </div>
    <div class="menu-item">
      <img src="soup.jpg" alt="Soup">
      <h3>Tomato Soup</h3>
      <p>Warm and creamy tomato soup.</p>
    </div>
    <div class="menu-item">
      <img src="sandwich.jpg" alt="Sandwich">
      <h3>Club Sandwich</h3>
      <p>Layered sandwich with chicken and bacon.</p>
    </div>
    <div class="menu-item">
      <img src="biriyani.jpg" alt="biriyani">
      <h3>mutton biriyani
      <p>made with traditional </p>
    </div>
    <div class="menu-item">
      <img src="ice cream.jpg" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops.</p>
    </div>
    <div class="menu-item">
      <img src="sambar.jpg" alt="sambar rice">
      <h3>sambar</h3>
      <p>hot and yummy.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Kabbilesh</p>
  </footer>
</body>
</html>
```



## OUTPUT:
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
