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
~~~
index.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Great India Kitchen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(244, 162, 97, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <div class="banner">
        <h1>Welcome to Great India Kitchen</h1>
        <p>Get your fork!We're on a roll!</p>
    </div>

    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <div class="welcome-section">
        <h2>About Us</h2>
        <p>Welcome to Great India Kitchen, A pleasant ambiance, whether it's cozy, lively, or elegant, contributes to a positive dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    
    <div class="food-images">
        <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2021/12/chicken-biryani-recipe.jpg" alt="Delicious Food 1">
        <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2022/03/butter-naan-500x500.jpg" alt="Delicious Food 2">
    </div>

    <footer>
        <p>&copy; DESIGNED BY: RAGUL K</p>
    </footer>
</body>
</html>

administration.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Great India Kitchen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #2a9d8f;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .admin-section {
            padding: 20px;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .admin-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .admin-card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .admin-card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="banner">
        <h1>Meet Our Administration</h1>
        <p>The team behind Great India Kitchen success</p>
    </div>

    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <div class="admin-section">
        <h2>Our Dedicated Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="https://www.newportri.com/gcdn/authoring/2013/03/15/NNDN/ghows-PJ-4a14c3b8-94cb-4569-a695-2e9c2b4fff35-7cbcbd5c.jpeg?width=1200&disable=upscale&format=pjpg&auto=webp" alt="Admin 1">
                <h3>Thomas Keller</h3>
                <p>C.E.O</p>
                <p>EMAIL:ThomasKeller@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="https://www.hollywoodreporter.com/wp-content/uploads/2024/01/AE.Rachael-Ray-H-2024.jpg?w=1296" alt="Admin 2">
                <h3>Rachael Ray</h3>
                <p>Head Chef</p>
                <p>EMAIL:RachaelRay@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="https://img.delicious.com.au/A8-nKp6v/w506-h506-cfill/del/2017/05/jamie-oliver-45518-2.jpg" alt="Admin 3">
                <h3>Jamie Oliver</h3>
                <p>MENU CURATOR</p>
                <p>EMAIL:Oliver@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="https://www.wewritebios.com/wp-content/uploads/2022/04/sample-restaurant-owner-bio.jpg" alt="Admin 4">
                <h3>THOMAS SHELBY</h3>
                <p>MARKETING MANAGER</p>
                <p>TOMMYSHELBY@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="https://static.independent.co.uk/s3fs-public/thumbnails/image/2014/08/28/16/michaelcaines.jpg" alt="Admin 5">
                <h3>Michael Caines</h3>
                <p>FINANCE MANAGER</p>
                <p>EMAIL:Caines@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="https://c8.alamy.com/comp/FR5HY8/portrait-smiling-restaurant-owner-behind-the-counter-FR5HY8.jpg" alt="Admin 6">
                <h3>Vicky Ratnam</h3>
                <p>PUBLIC RELATIONS OFFICER</p>
                <p>EMAIL:vicky@gmail.com</p>
            </div>
        </div>
    </div>
</body>
<footer>
    <p>&copy; DESIGNED BY:RAGUL K</p>
</footer>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Great India Kitchen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #2a9d8f;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .contact-section {
            padding: 20px;
        }
        .contact-details {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 500px;
            text-align: left;
        }
        .contact-details h2 {
            font-size: 20px;
            margin-bottom: 15px;
        }
        .contact-details p {
            font-size: 16px;
            margin: 5px 0;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Contact Us</h1>
        <p>Savoring every bite</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Contact Section -->
    <div class="contact-section">
        <h2>Get in Touch</h2>
        <div class="contact-details">
            <h2>Our Address</h2>
            <p>123 tiruvallur HIGHROAD</p>
            <p>CHENNAI</p>

            <h2>Phone</h2>
            <p>78920678959</p>

            <h2>Email</h2>
            <p><a href="mailto:info@nourishbistro.com">info@greatindia.com</a></p>
        </div>
    </div>
</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        h2 {
            background-color: #2a9d8f;
            color: white;
            padding: 20px;
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h2>Our Specialties</h2>
    <table>
        <caption>Delicious Menu Items</caption>
        <tr>
            <td><img src="https://www.cookwithmanali.com/wp-content/uploads/2019/05/Paneer-Butter-Masala.jpg" alt="Food Item 1"></td>
            <td>
                <h3>1. PANNER BUTTER MASALA</h3>
                <p>Paneer Butter Masala, also known as butter paneer is a rich & creamy
                     curry made with paneer, spices, onions, tomatoes, cashews and butter.</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://ontheflame.com/wp-content/uploads/2022/11/DSC_0207-2-scaled.jpg" alt="Food Item 2"></td>
            <td>
                <h3>2. VEG ROLL</h3>
                <p>Veg roll recipe for kids. These easy to make chapati rolls are delicious.</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://i.ytimg.com/vi/CXeIXRsrzJo/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLCsZ1fFAlYEgzZwXX7ivHe0oj-lxA" alt="Food Item 3"></td>
            <td>
                <h3>3. MOMUS</h3>
                <p>Momas is a commune in France. It is located in the Pyrénées-Atlantiques departement, in the region of Nouvelle-Aquitaine.</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://carveyourcraving.com/wp-content/uploads/2021/10/paneer-tikka-skewers-500x500.jpg" alt="Food Item 4"></td>
            <td>
                <h3>4. PANNER TIKKA</h3>
                <p>Paneer Tikka is popular Indian appetizer made with cubes of paneer & veggies
                     marinated with yogurt and spices. Traditionally it's grilled in a tandoor</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://b.zmtcdn.com/data/pictures/chains/8/19004068/c2395b62d1db5a4dd231be7684d16214.jpg" alt="Food Item 5"></td>
            <td>
                <h3>5. BOMBOO BIRYANI</h3>
                <p>Rice and chicken mixed in spices stuffed into a piece of raw bamboo
                     log that goes on natural fire till outer later becomes charcoal, is Bamboo ...</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUQlxuRwsJlV94nB5qNF6gj-Q_mdhU4bSD5g&s" alt="Food Item 6"></td>
            <td>
                <h3>6. STRAWBERRY MILKSHAKE</h3>
                <p>Strawberry milkshake recipe made in two ways
                     a classic milkshake prepared with milk, and a plant-based vegan shake made with almond milk.</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://images.stockcake.com/public/4/5/2/4525f7b0-131c-434c-89aa-1e63a8eb8839_large/exquisite-sushi-platter-stockcake.jpg" alt="Food Item 7"></td>
            <td>
                <h3>7. SUSHI PLATTER</h3>
                <p>Assortment of fresh sushi and sashimi served with soy sauce and wasabi.</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://www.allrecipes.com/thmb/dfGgVmzpoHhrsLjxGBa_0rIWyq0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/276304lava-cakeKim-e03d3bc55516400e8d05b8d84b524b73.jpg" alt="Food Item 8"></td>
            <td>
                <h3>8. LAVA CAKE</h3>
                <p>Lava cake is a decadent individual dessert served warm to reveal
                     a molten chocolate center. It may just be the best chocolate dessert you've ever had!</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://femina.wwmindia.com/content/2023/jul/sizzlingchocolatebrownie-chefsanjyotkeer16885606281688560637.jpg" alt="Food Item 9"></td>
            <td>
                <h3>9. SIZZLING BROWNIE</h3>
                <p>It is a chocolate brownie with a scoop of ice cream on top served with a generous
                     pouring of melted chocolate on the ice-cream. It is served on hot sizzler ...</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://static.toiimg.com/thumb/53094926.cms?width=1200&height=900" alt="Food Item 10"></td>
            <td>
                <h3>10. CHILLI CHICKEN</h3>
                <p>Chilli chicken is a popular Indo-Chinese dish that uses chicken, and is of Hakka Chinese heritage.</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://content.jdmagicbox.com/v2/comp/chennai/a8/044pxx44.xx44.190716183052.z1a8/catalogue/sandwitch-chennai-fast-food-delivery-services-44jx9vznst.jpg" alt="Food Item 11"></td>
            <td>
                <h3>11. SANDWITCH</h3>
                <p>A sandwich is a food item made up of two or more slices of bread with a filling in between.DD</p>
            </td>
        </tr>
        <tr>
            <td><img src="https://beamingbaker.com/wp-content/uploads/2022/01/IGTmaybe-virgin-mojito-recipe-mojito-mocktail-2.jpg" alt="Food Item 12"></td>
            <td>
                <h3>12. MOJITO MOCKTAIL</h3>
                <p>Refreshing blend of lime, mint, and sparkling soda.</p>
            </td>
        </tr>
    </table>
    <footer>
        <p>&copy; DESIGNED BY: RAGUL K</p>
    </footer>
</body>
</html>
~~~



# OUTPUT:
<img width="804" height="418" alt="image" src="https://github.com/user-attachments/assets/8d02f588-ee90-4a77-b727-5a9d7af71adc" />
<img width="819" height="433" alt="image" src="https://github.com/user-attachments/assets/80a79dcb-06b3-4ddd-a378-75ef53864b68" />
<img width="822" height="445" alt="image" src="https://github.com/user-attachments/assets/9a71443f-7db1-48db-ba98-49ffa400ac5b" />
<img width="806" height="428" alt="image" src="https://github.com/user-attachments/assets/53d0747d-a269-4ef9-8447-306e3b9e861d" />
<img width="814" height="433" alt="image" src="https://github.com/user-attachments/assets/e4e7dbaf-4f4e-4d14-981a-08971e74bcbb" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
