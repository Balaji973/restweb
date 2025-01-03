# Ex.07 Restaurant Website
## Date:23.12.2024

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin : 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-image: url('s.jpg');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #343a40;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #6f7275;
        }
        .container {
            padding: 20px;
            
        }
        .menu-items, .admin, .contact {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .menu-item, .admin-card {
            border: 1px solid #000000;
            border-radius: 5px;
            padding: 10px;
            text-align: center;
            flex: 1 1 calc(25% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            
        }
        .menu-item img, .admin-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to tasty spot</h1>
        <p>  It’s finger lickin’ good </p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#administration">Administration</a>
        <a href="#contact">Contact Us</a>
    </nav>
    
    <section id="home" class="container">
        <h2>Home</h2>
        <p>wake up your taste bud by our food<br> Your journey to deliciousness starts here.<br>A destination for food lovers, a junction for taste.</p>
    </section>

    <section id="menu" class="container">
        <h2>Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="im3.jpg" alt="Dish 1">
                <p>Bucket fry Chicken</p>
            </div>
            <!-- Repeat for 12 items -->
            <div class="menu-item">
                <img src="grill.jpg" alt="Dish 12">
                <p>grill chicken</p>
            </div>
            <div class="menu-item">
                <img src="Screenshot 2024-12-25 133823.png" alt="Dish 12">
                <p>Special Biriyani</p>
            </div>
            <div class="menu-item">
                <img src="roll.jpg" alt="Dish 12">
                <p>shawarma</p>
            </div>
            <div class="menu-item">
                <img src="cake.jpg" alt="Dish 12">
                <p>Chocolate Lava Cake</p>
            </div>
            <div class="menu-item">
                <img src="fries.jpg" alt="Dish 12">
                <p>potato fries</p>
            </div>
            <div class="menu-item">
                <img src="ice.jpg" alt="Dish 12">
                <p>deserts</p>
            </div>

            <div class="menu-item">
                <img src="Screenshot 2024-12-25 130913.png" alt="Dish 12">
                <p>cheesy chicken burger</p>
            </div>
            <div class="menu-item">
                <img src="im2.jpg" alt="Dish 12">
                <p>Combo +3</p>
            </div>
            <div class="menu-item">
                <img src="pi.jpg" alt="Dish 12">
                <p>Margherita Pizza</p>
            </div>
            <div class="menu-item">
                <img src="paro.jpg" alt="Dish 12">
                <p>Parotta</p>
            </div>
            <div class="menu-item">
                <img src="pep.jpg" alt="Dish 12">
                <p>Pepsi</p>
            </div>
            
        </div>
    </section>

    <section id="administration" class="container">
        <h2>Administration</h2>
        <div class="admin">
            <div class="admin-card">
                <img src="Screenshot 2024-12-25 135141.png" alt="Admin 1">
                <p> SColonel Harland- Manager</p>
            </div>
            <!-- Repeat for 6 people -->
            <div class="admin-card">
                <img src="ch.jpg" alt="Admin 6">
                <p>our food Chefs</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Address: 248 food court,Saveetha Nagar,Chennai</p>
        <p>Phone: 011-39827985</p>
        <p>Email: contact@foodlovers.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Taste spot ||  Balaji J</p>
    </footer>
</body>
</html>

'''

## OUTPUT:
![alt text](<Screenshot 2024-12-25 143047.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
