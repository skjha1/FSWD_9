## HTML
```html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">Header</header>
    <aside class="sidebar">Sidebar</aside>
    <main class="main-content">Main content</main>
    <footer class="footer">Footer</footer>
</body>
</html>



```
--------------------------------------------------------
## CSS
```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, Helvetica, sans-serif;
}

header, aside, main, footer {
    padding: 20px;
    border: 1px solid #ccc;
}

.header {
    background-color: #4caf50;
    color: white;
    text-align: center;
}

.sidebar {
    background-color: #f4f4f4;
}

.main-content {
    background-color: #fff;
}

.footer {
    background-color: #4caf50;
    color: white;
    text-align: center;
}

body {
    display: grid;
    grid-template-areas: 
    "header header header"
    "sidebar main main"
    "footer footer footer"
    ;
    grid-template-columns: 1fr 3fr;
    grid-template-rows: auto 1fr auto;
    height: 100vh;
}
.header {
    grid-area: header;
}

.sidebar {
    grid-area: sidebar;
}

.main-content {
    grid-area: main;
}
.footer{
    grid-area: footer;
}


/* Media query for tablet devices  (max-width: 1024px) */

@media (max-width: 1024px) {
    body {
        grid-template-areas: 
        "header header"
        "sidebar main"
         "footer footer"
        ;
        grid-template-columns: 1fr 2fr;
    }
}


/* Media query for mobile devices  (max-width: 768px) */

@media (max-width: 768px) {
    body {
        grid-template-areas: 
        "header"
        "main"
        "sidebar"
        "footer"
        ;
        grid-template-columns: 1fr;
        grid-template-rows: auto 1fr auto auto;
    }

    header, aside, main, footer {
        padding: 15px;
        border: none;
    }

    .header, .footer {
        text-align: left;
    }
}

```
