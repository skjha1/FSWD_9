### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        a {
            text-decoration: none;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .column-name {
            background-color: #e0f7fa;
        }

        .column-age {
            text-align: center;
        }

        .column-city {
            font-style: italic;
        }

    </style>
</head>
<body>
    <h1>This is heading level 1</h1>
    <h2>This is heading level 2</h2>
    <h3>This is heading level 3</h3>
    <h4>This is heading level 4</h4>
    <h5>This is heading level 5</h5>
    <h6>This is heading level 6</h6>

    <p>This is a paragraph of text. Here's a <a href="https://www.google.com" >link</a> to the google website</p>

    <ul>
        <li>Unordered list item 1</li>
        <li>Unordered list item 2</li>
        <li>Unordered list item 3</li>
        <li>Unordered list item 4</li>
    </ul>

    <ol>
        <li>ordered list item 1</li>
        <li>ordered list item 2</li>
        <li>ordered list item 3</li>
        <li>ordered list item 4</li>
    </ol>

    <dl>
        <dt>HTML</dt>
        <dd>A standared markup language for creating the web pages</dd>
        <dt>CSS</dt>
        <dd>A standared markup language for creating the web pages</dd>
    </dl>
  <img src="image/image.jpg" alt="Sample image">
    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>

    <form action="/submit-form" method="post">
        <label for="fname">First Name: </label><br>
        <input type="text" id="fname" name="fname" placeholder="Enter your first name"><br>
        <label for="lname">Last Name: </label><br>
        <input type="text" id="lname" name="lname" placeholder="Enter your last name"><br>
        <input type="submit" value="Submit"><br>
        <button type="submit">Submit</button>
    </form>



    <h1>Column-wise table example</h1>


    <table>
        <thead>
            <tr>
                <th class="column-name">Name</th>
                <th class="column-age">Age</th>
                <th class="column-city">City</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="column-name">Sanjana</td>
                <td class="column-age">16</td>
                <td>Delhi</td>
            </tr>


            <tr>
                <td class="column-name">Varun</td>
                <td class="column-age">17</td>
                <td class="column-city">Chennai</td>
            </tr>

            <tr>
                <td class="column-name">Ram</td>
                <td class="column-age">17</td>
                <td class="column-city">Chennai</td>
            </tr>

            <tr>
                <td class="column-name">Amit</td>
                <td class="column-age">17</td>
                <td class="column-city">Chennai</td>
            </tr>
        </tbody>
    </table>   
</body>
</html>

```
