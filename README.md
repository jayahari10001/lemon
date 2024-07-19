## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.jpeg" alt="Little Lemon Logo">
            <h1>Little Lemon</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>30% Off This Weekend</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
    </section>
    <section class="content">
        <div class="card">
            <img src="menu.jpeg" alt="New Menu">
            <h3>Our New Menu</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
            <a href="#">See our new menu</a>
        </div>
        <div class="card">
            <img src="book.jpeg" alt="Book a Table">
            <h3>Book a table</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
            <a href="#">Book your table now</a>
        </div>
        <div class="card">
            <img src="hour.jpeg" alt="Opening Hours">
            <h3>Opening Hours</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices.</p>
            <p>Mon - Fri: 2pm - 10pm<br>
            Sat: 2pm - 11pm<br>
            Sun: 2pm - 9pm</p>
        </div>
    </section>
    <footer>
        <img src="logo.jpeg" alt="Little Lemon Logo">
        <p>Copyright Little Lemon</p>
    </footer>
</body>
</html>
```
## styles.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #ffffff;
}

.logo {
    display: flex;
    align-items: center;
}

.logo img {
    height: 50px;
    margin-right: 10px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 50px 20px;
    background-image: url('hero1.jpeg');
    background-size: cover;
    background-position: center;
    color: white;
}

.hero h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    max-width: 600px;
    margin: 0 auto;
}

.content {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: #ffffff;
}

.card {
    background-color: #ffe4c4;
    padding: 20px;
    width: 20%;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.card img {
    width: 100%;
    height: auto;
    margin-bottom: 15px;
}

.card h3 {
    margin-top: 0;
}

.card a {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
}

footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #ffffff;
    border-top: 1px solid #e1e1e1;
}

footer img {
    height: 40px;
}

footer p {
    margin: 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/f6501ab2-f05c-4f58-bae2-d018eb192a1a)

