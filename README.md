 menu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menus</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #f8f8f8;
            padding: 20px;
        }
        .menu {
            width: 400px;
            height: 550px;
            padding: 20px;
            margin: 10px;
            border: 3px solid #333;
            border-radius: 10px;
            color: white;
            font-family: Arial, sans-serif;
            background-size: cover;
            background-position: center;
        }
        .breakfast {
            background-image: url('https://zaxid.net/resources/photos/news/1200x675_DIR/202405/1585459.jpg?202503151801');
        }
        .lunch {
            background-image: url('https://vikna.tv/wp-content/uploads/2022/06/05/reczept-smachnogo-obidu.jpg');
        }
        .dinner {
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRygf_LVqCW1VXha3TBX430VuFER0hxSNFUDQ&s');
        }
        h2 {
            text-align: center;
            background: rgba(0, 0, 0, 0.6);
            padding: 10px;
            border-radius: 5px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            background: rgba(0, 0, 0, 0.5);
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="menu breakfast">
        <h2>Breakfast Menu</h2>
        <ul>
            <li>Pancakes with Maple Syrup</li>
            <li>Scrambled Eggs with Toast</li>
            <li>Fruit Salad</li>
            <li>Orange Juice</li>
            <li>Coffee</li>
        </ul>
    </div>
    <div class="menu lunch">
        <h2>Lunch Menu</h2>
        <ul>
            <li>Grilled Chicken Sandwich</li>
            <li>Caesar Salad</li>
            <li>Tomato Soup</li>
            <li>Iced Tea</li>
            <li>Lemonade</li>
        </ul>
    </div>
    <div class="menu dinner">
        <h2>Dinner Menu</h2>
        <ul>
            <li>Steak with Mashed Potatoes</li>
            <li>Grilled Salmon</li>
            <li>Vegetable Stir Fry</li>
            <li>Red Wine</li>
            <li>Chocolate Cake</li>
        </ul>
    </div>
</body>
</html>
