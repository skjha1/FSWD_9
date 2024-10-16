```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header class="header">Header</header>
        <main class="main-content">Main Content</main>
        <footer class="footer">Footer</footer>
    </div>
</body>
</html>

```


```css
html {
  font-size: 16px;
}

.container {
  width: 90%;  /* 9-% of the viewport width */
  margin: 0 auto; /* center container */
  padding: 1rem; /* 16px padding */
}

.header {
  background-color: #4caf50;
  padding: 1em;  /* 16px padding */
  font-size: 2rem;  /* 16 * 2 = 32px */
  text-align: center;
}

.main-content {
  background-color: #f1f1f1;
  padding: 2em;  /* 32px padding */
  font-size: 1rem;  /* 16px */
  margin-bottom: 20px;
  line-height: 1.5;
}

.footer{
  background-color: #333;
  color: white;
  padding: 1em;
  text-align: center;
  font-size: 1em;
}

@media (max-width: 600px) {
  html {
    font-size: 14px;
  }
  .container {
    width: 100%;
    padding: 0.5em; 

  }
  .header {
    font-size: 1.5em;
    padding: 0.5em; 
  }
  .main-content {
    padding: 1rem;
  }
  .footer {
    font-size: 0.875rem;
    padding: 0.5em;
  }

}

@media (max-width: 601px) and  (max-width: 992px){
  html {
    font-size: 15px;
  }
  .container {
    width: 95%;
    padding: 1rem; 

  }
  .header {
    font-size: 1.75em;
    padding: 1em; 
  }
  .main-content {
    padding: 1.5rem;
  }
  .footer {
    font-size: 1em;
    padding: 1em;
  }

}

```

### **Summary of Difference**


|unit|relative to|use case|real-life example |
|----|-----------|--------|------------------|

|em|current_element font size|Padding, margin, scalable component|Frame size relative to artwork|


// rem     Root(<html>) font size          consistent sizing accross the document      Room heights relative to building base


// %       Parent element size             Responsive width and height                 Picture size relative to wall space






```
