# Ex.07 Restaurant Website
## Date:09-12-2024

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
```
<html>
<head>
    <title>ABC Restaurant</title>
    <style>
        body 
        {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            color: black;
        }
        header 
        {
            background-color: aqua;
            color: white;
            padding: 15px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: auto;
        }
        header img 
        {
            max-width: 60px;
            height: auto;
        }
        header div 
        {
            text-align: center;
            flex-grow: 1;
        }
        header h1 
        {
            margin: 0;
            font-size: 2rem;
        }
        header p 
        {
            margin: 0;
            font-size: 1rem;
        }
        section 
        {
            padding: 30px;
            text-align: center;
        }
        section h2 
        {
            font-size: 2rem;
            color: aqua;
        }
        .menu-container 
        {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 800px;
            margin: auto;
        }
        .menu-item 
        {
            width: 100%;
            max-width: 400px;
            padding: 20px;
            background-color: white;
            border: 1px solid whitesmoke;
            border-radius: 10px;
            margin: 15px 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .menu-item h3 
        {
            color: aqua;
        }
        .menu-item img 
        {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
            border-radius: 8px;
        }
        .menu-item p 
        {
            margin: 10px 0;
        }
        .menu-item .allergens 
        {
            font-size: 0.8rem;
            color: gray;
            margin-top: 15px;
        }
        .contact-section 
        {
            padding: 40px;
            background-color: white;
            text-align: center;
        }
        .contact-section h2 
        {
            color: aqua;
        }
        footer 
        {
            background-color: aqua;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div>
            <h1>ABC RESTAURANT</h1>
            <p>Morden Dining & Healthy Food </p>
        </div>
    </header>

    <section>
        <h2>About Our Restaurant</h2>
        <p>"At ABC Restaurant, every bite tells a story of flavor, passion, and perfection."</p>
    </section>

    <section>
        <h2>Menu</h2>
        <div class="menu-container">
            <div class="menu-item">
                <h3>Breakfast</h3>
                <p>Starter: Bread Toast</p>
                <img src="Bread Toast.jpg" alt="Bread Toast">
                <p>Main: Dosa</p>
                <img src="Dosa.jpg" alt="Dosa">
                <p>Main: Idli </p>
                <img src="Idli-Sambar.jpg" alt="Idli">
                <p>Additional Dessert: Crème Brûlée</p>
                <img src="Creme Brulee.jpg" alt="Crème Brûlée">
                <p class="allergens">*Allergens: gluten, seafood, dairy</p>
            </div>
            <div class="menu-item">
                <h3>Lunch</h3>
                <p>Starter: Soup</p>
                <img src="Vegetable-Soup.jpg" alt="Soup">
                <p>Main: Meals</p>
                <img src="Meals.jpg" alt="Meals">
                <p>Drinks: Coffee</p>
                <img src="Coffee.jpg" alt="Coffee">
                <p>Additional Dessert: Berry Panna Cotta</p>
                <img src="Berry Panna Cotta.jpg" alt="Berry Panna Cotta">
                <p class="allergens">*Allergens: dairy, eggs</p>
            </div>
            <div class="menu-item">
                <h3>Dinner</h3>
                <p>Starter: Stuffed Mushrooms</p>
                <img src="Stuffed Mushroom.jpg" alt="Stuffed Mushrooms">
                <p>Main: Grilled Chicken</p>
                <img src="Grilled Chicken.jpg" alt="Grilled Chicken">
                <p>Main: Fried Rice </p>
                <img src="Fried Rice.jpg" alt="Fried Rice">
                <p>Additional Dessert: Tiramisu</p>
                <img src="Tiramisu.jpeg" alt="Tiramisu">
                <p class="allergens">*Allergens: dairy, nuts</p>
            </div>
        </div>
    </section>

    <section class="contact-section">
        <h2>Contact :</h2>
        <p>Address: ABC, 19/20 Royal Street, Anna Nagar, Chennai , TamilNadu</p>
        <p>Phone: (91) 938-7229</p>
        <p>Email: hi@abc.com</p>
        <p>Open Hours: 08:00 am - 10:00 pm</p>
    </section>

    <footer>
        <p>&copy; ABC Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![alt text](1.png)
![alt text](2.png)
![alt text](3.png) 
![alt text](4.png) 
![alt text](5.png)
![alt text](6.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
