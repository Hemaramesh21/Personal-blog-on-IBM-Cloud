 Here’s The Code For PERSONAL TRAVEL BLOG Which Allows Us To Upload Pictures And Explore Places By The Users

<!DOCTYPE html>
<html>
<head>
    <title>My Travel Blog</title>
    <style>
        /* Add your custom CSS styles here */
        body {
            font-family: Arial, sans-serif;
        }
        header {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #333;
            color: #fff;
            padding: 10px;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav li {
            margin: 0 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
        }
        section {
            margin: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Travel Blog</h1>
        <p>Your gateway to exploring amazing destinations</p>
    </header>

    <nav>
        <ul>
            <li><a href="#paris">Paris</a></li>
            <li><a href="#tokyo">Tokyo</a></li>
            <li><a href="#newyork">New York</a></li>
        </ul>
    </nav>

    <section id="paris">
        <h2>Paris, France</h2>
        <p>Paris is a beautiful city known for its iconic Eiffel Tower, Louvre Museum, and charming streets.</p>
        <img src="paris.jpg" alt="Eiffel Tower in Paris">
        <p>Check out this <a href="https://www.paris-tourism.com/">official Paris tourism website</a> for more information.</p>
    </section>

    <section id="tokyo">
        <h2>Tokyo, Japan</h2>
        <p>Tokyo is a bustling metropolis with a rich blend of tradition and modernity. Don't miss the Senso-ji Temple and Shibuya Crossing!</p>
        <img src="tokyo.jpg" alt="Shibuya Crossing in Tokyo">
        <p>Explore more about Tokyo <a href="https://www.gotokyo.org/en/">here</a>.</p>
    </section>

    <section id="newyork">
        <h2>New York City, USA</h2>
        <p>New York City is a city that never sleeps. Explore Central Park, Times Square, and the Statue of Liberty.</p>
        <img src="newyork.jpg" alt="Statue of Liberty in New York">
        <p>Visit the <a href="https://www.nycgo.com/">NYC & Company website</a> for planning your trip.</p>
    </section>

    <footer>
        <p>&copy; 2023 My Travel Blog</p>
    </footer>
</body>
</html>