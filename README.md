# Ex.07 Restaurant Website
# Date:
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
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Wakanda Table</title>
      <style>
        body {
          margin: 0;
          font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
          background-color: #000;
          color: #eee;
        }
        header {
          background-color: #0e0f0e;
          padding: 20px;
          text-align: center;
        }
        nav {
          background-color: #333;
          display: flex;
          justify-content: center;
          gap: 40px;
          padding: 10px 0;
        }
        nav a {
          color: white;
          text-decoration: none;
          font-weight: bold;
        }
        .banner {
          background: url('/mnt/data/1f161b39-e971-4894-a0a7-236b1cb36920.png') center/cover no-repeat;
          color: white;
          padding: 60px 20px;
          text-align: center;
          font-size: 2rem;
          border-radius: 10px;
          margin: 20px;
        }
        .container {
          display: flex;
          flex-wrap: wrap;
          gap: 20px;
          justify-content: center;
          margin: 20px;
        }
        .card {
          background-color: #1a1a1a;
          padding: 15px;
          border-radius: 10px;
          width: 300px;
          color: #eee;
        }
        .card img {
          width: 100%;
          border-radius: 10px;
        }
        footer {
          text-align: center;
          padding: 20px;
          font-size: 0.8rem;
          color: #aaa;
        }
      </style>
    </head>
    <body>
      <header>
        <h1>🕷️ Wakanda Table 🕷️</h1>
      </header>
      <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#admin">Administration</a>
        <a href="#contact">Contact Us</a>
      </nav>
    
      <section id="home">
        <div class="banner">30% Off This Weekend – Come Taste the Zest!</div>
        <div class="container">
          <div class="card">
            <h2>Our New Menu</h2>
            <img src="c:\Users\admin\Downloads\129010121-assorted-indian-food-on-black-background-indian-cuisine-top-view-with-copy-space.jpg" alt="Grill">
            <p>Discover sizzling new dishes and mouth-watering delights fresh off the grill.</p>
          </div>
          <div class="card">
            <h2>Book a Table</h2>
            <img src="c:\Users\admin\Downloads\360_F_278693728_O7t0fe2oDwwucHisBR1i8UhVxE5N229G.jpg" alt="Salad">
            <p>Reserve your spot now and enjoy a Mediterranean feast like no other.</p>
          </div>
          <div class="card">
            <h2>Opening Hours</h2>
            <p>Mon-Fri: 2pm-10pm<br>Sat: 2pm-11pm<br>Sun: 2pm-9pm</p>
          </div>
        </div>
      </section>
    
      <section id="menu">
        <h2 style="text-align:center">Our Menu</h2>
        <div class="container">
          <div class="card"><h3>Margherita Pizza</h3><img src="c:\Users\admin\Downloads\PIZZA-MARGHERITA.jpg" alt="Pizza" /><p>Classic Neapolitan pizza with fresh basil, mozzarella, and tomato sauce.</p></div>
          <div class="card"><h3>Spaghetti Carbonara</h3><img src="c:\Users\admin\Downloads\11973-spaghetti-carbonara-ii-DDMFS-4x3-6edea51e421e4457ac0c3269f3be5157.jpg" alt="Pasta" /><p>Rich and creamy spaghetti tossed with pancetta and a parmesan-egg sauce.</p></div>
          <div class="card"><h3>Grilled Chicken</h3><img src="c:\Users\admin\Downloads\Tandoori-Chicken-20.jpg" alt="Chicken" /><p>Juicy grilled chicken served with herbs and a side of lemon butter sauce.</p></div>
          <div class="card"><h3>Caesar Salad</h3><img src="c:\Users\admin\Downloads\caesar-salad.jpg" alt="Salad" /><p>Romaine lettuce, parmesan, croutons, and Caesar dressing.</p></div>
          <div class="card"><h3>Fish Tacos</h3><img src="c:\Users\admin\Downloads\53729-fish-tacos-DDMFS-4x3-b5547c67c6f0432da06ad8f905e82c1e.jpg" alt="Tacos" /><p>Grilled fish in soft tortillas with tangy slaw and chipotle sauce.</p></div>
          <div class="card"><h3>Veggie Wrap</h3><img src="c:\Users\admin\Downloads\4526733-45129f82ed554ea1be3ac980d096a6f1.jpg" alt="Wrap" /><p>Fresh veggies wrapped in a soft tortilla with hummus spread.</p></div>
          <div class="card"><h3>Lamb Chops</h3><img src="c:\Users\admin\Downloads\perfectly-grilled-lamb-rib-or-loin-chops-recipe-hero-03-262fe2defc7c491688cb2d363dad3446.jpg" alt="Lamb" /><p>Char-grilled lamb chops seasoned with garlic and rosemary.</p></div>
          <div class="card"><h3>Beef Burger</h3><img src="c:\Users\admin\Downloads\TheUltimateBurgerwBacon_RecipePic-1200x675.jpg" alt="Burger" /><p>Thick beef patty, cheddar cheese, lettuce, and tomato on a brioche bun.</p></div>
          <div class="card"><h3>Tomato Soup</h3><img src="c:\Users\admin\Downloads\tomato-soup-recipe.jpg" alt="Soup" /><p>Creamy tomato soup served with a side of garlic bread.</p></div>
          <div class="card"><h3>Mango Smoothie</h3><img src="c:\Users\admin\Downloads\Mango-Strawberry-Layered-Smoothie.png" alt="Smoothie" /><p>Refreshing blend of ripe mangoes and Greek yogurt.</p></div>
          <div class="card"><h3>Chocolate Cake</h3><img src="c:\Users\admin\Downloads\2-hersheys-perfectly-chocolate-chocolate-cake-recipe-hero.jpg" alt="Cake" /><p>Moist chocolate cake topped with rich ganache.</p></div>
          <div class="card"><h3>Ice Cream Sundae</h3><img src="c:\Users\admin\Downloads\8hEwLDNaTS682SgylIKU_1.1sundaeredo.jpg" alt="Ice Cream" /><p>Classic sundae with vanilla ice cream, hot fudge, and nuts.</p></div>
        </div>
      </section>
    
      <section id="admin">
        <h2 style="text-align:center">Our Team</h2>
        <div class="container">
          <div class="card"><h3>Chef DiCaprio</h3><p>Master of Italian cuisine and the creative force behind our seasonal dishes.</p></div>
          <div class="card"><h3>Manager Johnny Depp</h3><p>Ensures smooth operations and customer satisfaction with a smile.</p></div>
          <div class="card"><h3>Head Waiter Dong Lee</h3><p>Leads the service team with professionalism and attention to detail.</p></div>
          <div class="card"><h3>Barista Leo Das</h3><p>Coffee connoisseur serving espresso perfection in every cup.</p></div>
          <div class="card"><h3>Pastry Chef AlPacino</h3><p>Bakes delightful pastries and desserts that melt in your mouth.</p></div>
          <div class="card"><h3>Hostess Elizabeth Grant</h3><p>Warmly welcomes every guest and makes them feel right at home.</p></div>
        </div>
      </section>
    
      <section id="contact">
        <h2 style="text-align:center">Contact Us</h2>
        <div class="container">
          <div class="card">
            <h3>📍 Address</h3>
            <p>123, Wayne Street<br>Gotham City</p>
            <h3>📞 Phone</h3>
            <p>+1 (555) 123-4567</p>
            <h3>📧 Email</h3>
            <p>contact@wakandatable.com</p>
          </div>
        </div>
      </section>
    
      <footer>
        &copy; 2025 Wakanda Table | Designed and Developed by <span style="color:red">Sanjeev Kumar</span>
      </footer>

# OUTPUT:
![437055010-5cf169c4-ebb2-4159-9296-5f3ffabac982](https://github.com/user-attachments/assets/112165d9-5e88-422c-8a1e-7772975ef4cc)
![437055006-e8f7881d-08e9-4210-be89-16db9dc6bd91](https://github.com/user-attachments/assets/f23badbc-d3cb-42ec-90eb-3af9f5079f30)
![437055019-145323ae-45e9-43c7-bb71-bab942f1d02c](https://github.com/user-attachments/assets/70124a97-0104-41d3-b97c-1f3732f6eb58)
![437054971-6762ac65-4380-4348-be97-330650ab5bb9](https://github.com/user-attachments/assets/3d3d16ad-8394-4f59-9066-a420901cc377)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
