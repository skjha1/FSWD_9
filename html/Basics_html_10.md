### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }   
        a {
            text-decoration: none;
            color: #1a0dab;
        }
        a:hover {
            text-decoration: underline;
            color: #d93025;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th,td {
            border: 1px solid #333;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #4caf50;
            color: white;
        }

        form {
            margin: 20px 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        input[type="submit"], button {
            background-color: #4caf50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-right: 10px;
        }
        input[type="submit"]:hover, button:hover {
            background-color: #4ca049;
        }
    </style>
</head>
<body>
    <h1>This is a heading level 1</h1>
    <h2>This is a geading level 2</h2>
    <h3>This is a heading level 3</h3>
    <h4>This is a geading level 4</h4>
    <h5>This is a heading level 5</h5>
    <h6>This is a geading level 6</h6>


    <p>This is a paragraph of text, here's is a <a href="https://www.google.com">link</a> to the google website</p>

    <ul>
        <li>Unordered List item 1</li>
        <li>Unordered List item 2</li>
        <li>Unordered List item 3</li>
        <li>Unordered List item 4</li>
    </ul>


    <ol>
        <li>Ordered List item 1</li>
        <li>Ordered List item 2</li>
        <li>Ordered List item 3</li>
        <li>Ordered List item 4</li>
    </ol>

    <dl>
        <dt>HTML</dt>
        <dd>A standared markup language for creating a web page</dd>
        <dt>CSS</dt>
        <dd>A standared markup language for creating a web page</dd>
    </dl>


    <img src="image/sample-image.jpg" alt="A sample Image">

    <h2>Sample Table example</h2>

    <table>
        <thead>
            <tr>
                <th>Product</th>
                <th>Price ₹</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Apple</td>
                <td>150</td>
            </tr>

            <tr>
                <td>Banana</td>
                <td>50</td>
            </tr>
            <tr>
                <td>Cherries</td>
                <td>200</td>
            </tr>
        </tbody>
    </table>

    <h2>Contact Us</h2>

    <form action="/subit-form" method="post">
        <label for="fname">First Name: </label>
        <input type="text" id="fname" name="fname" placeholder="Enter your first name">

        <label for="lname">Last Name: </label>
        <input type="text" id="lname" name="lname" placeholder="Enter your first name">

        <input type="submit" value="Submit">
        <button type="reset">Reset</button>
    </form>


</body>
</html>



```
