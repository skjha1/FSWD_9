```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive CSS Grid Layout</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="grid-container">
        <header class="header">My website</header>
        <nav class="navbar">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Service</a>
            <a href="#">Contact</a>
        </nav>
        <main class="main-content">
            <h1>Welcome to My website</h1>
            <p>This is a main content area. Here you can add articles, Images, or any other information you want to display</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident dolore vel, nostrum quas aut nihil adipisci tenetur consequatur. Alias pariatur excepturi iusto. Aspernatur, consequuntur beatae! Est numquam perspiciatis inventore aliquam.</p>
        </main>

        <aside class="sidebar">
            <h2>Sidebar</h2>
            <p>This is a sidebar. you can place additional links, advertisments, or other supplementry information here.</p>
            <ul>
                <li><a href="#">Link 1</a></li>
                <li><a href="#">Link 2</a></li>
                <li><a href="#">Link 3</a></li>
            </ul>
        </aside>

        <footer class="footer">
            &copy; 2024 My website. All rights reserved.
        </footer>
    </div>
</body>
</html>
```


```css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* Basic styling for body  */

body {
  font-family: Arial, Helvetica, sans-serif ;
  line-height: 1.6;
  background-color: #f4f4f4;
}

.grid-container {
  display: grid;
  grid-template-areas: 
  "header"
  "navbar"
  "main"
  "sidebar"
  "footer"
  ;
  grid-template-columns: 1fr;
  grid-gap: 10px;
  max-width: 1200px;
  margin: auto;
  padding: 10px;
}

.header{
  grid-area: header;
  background-color: #4caf50;
  color: white;
  padding: 20px;
  text-align: center;
  font-size: 1.5em;
}

.navbar {
  grid-area: navbar;
  background-color: #333;
  overflow: hidden;
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: #ddd;
  color: black;
}

.main-content {
  grid-area: main;
  background-color: white; 
  padding: 20px;
}

.sidebar {
  grid-area: sidebar;
  background-color: #f1f1f1;
  padding: 20px;
}

.footer{
  grid-area: footer;
  background-color: #4caf50;
  color: white;
  padding: 20px;
  text-align: center;
}

@media (max-width: 768px) {
  .grid-container {
    grid-template-areas: 
    "header header"
    "navbar navbar"
    "main sidebar"
    "footer footer"
    ;
  }
}


@media (max-width: 1024px) {
  .grid-container {
    grid-template-areas: 
    "header header header"
    "navbar navbar navbar"
    "main sidebar sidebar"
    "footer footer footer"
    ;
    grid-template-columns: 3fr 1fr 1fr;
  }
}



```
