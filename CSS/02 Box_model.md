```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edtech Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1>Edtech plateform</h1>
    </header>

    <nav class="navbar">
        <a href="#">Home</a>
        <a href="#">Courses</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <section class="course-list">
            <div class="course">
                <h2>Course 1</h2>
                <p>Learn the basics of Web developemt</p>
            </div>

            <div class="course">
                <h2>Course 2</h2>
                <p>Advanced Javascript techniques</p>
            </div>

            <div class="course">
                <h2>Course 3</h2>
                <p>Introduction to Python progranming</p>
            </div>
        </section>
    </main>
    <aside class="sidebar">
        <h3>Upcoming Events</h3>
        <p>Webinar on CSS Grid</p>
        <p>Javascript workshop - 15 Oct</p>
    </aside>
    <footer class="footer">
        <p>&copy; 2024 Edtech plateform. All rights reserved.</p>
    </footer>
</body>
</html>

```


```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    display: grid;
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    line-height: 1.6;
    grid-template-rows: auto 1fr auto auto;
    grid-template-columns: 1fr 3fr;
    grid-template-areas: 
    "header header"
    "nav main"
    "nav sidebar"
    "footer footer"
    ;
}

.header{
    grid-area: header;
    background-color: #4caf50;
    color: white;
    padding: 20px;
    text-align: center;
    margin-bottom: 20px;
    border-radius: 10px;
}

.course-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 20px;
}

.course {
    background-color: white;
    border: 1px solid #ccc;
    padding: 20px;
    margin: 10px;
    width: 300px;
    border-radius: 5px;
    box-shadow: 0 0 0 0 rgba(0, 0, 0, 0.1);
}

.course h2 {
    margin-bottom: 10px;
    color: #4caf50;
}

.navbar {
    grid-area: nav;
    background-color: #fff;
    padding: 20px;
    display: flex;
    flex-direction: column;
    gap: 15px;
    border-radius: 10px;
}

.navbar a {
    color: #333;
    text-decoration: none;
    padding: 10px 20px;
    background-color: #e7e9eb;
    border-radius: 5px;
    transition: background-color 0.5s;
}

.navbar a:hover {
    background-color: #4caf50;
    color: white;
}

.footer{
    background-color: #4caf50;
    color: white;
    padding: 20px;
    text-align: center;
    margin-bottom: 20px;
    grid-area: footer;
}


```
