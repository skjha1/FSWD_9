<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ultimate fitness gym</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: flex;
            margin: 0 10px;
        }

        nav ul li a{
            color: white;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }

        section, aside {
            margin: 20px 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th td {
            padding: 10px;
            text-align: left;
        }

        form {
            margin-top: 20px;
        }
        form label, form input, form textarea, form button {
            display: block;
            margin: 10px 0;
        }
        
    </style>
</head>
<body>
    <header>
        <h1>Ultimate Fitness Gym</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#schedule">Schedule</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>


    <main>
        <section id="home">
            <h2>Welcome to Ultimate Fitness Gym</h2>
            <p>Your journey to a healthier life starts here. Join us and get the access to top notch equipmens experienced trainer's and variety of classes that suits your fitness goals. </p>
            <img src="data:image/jpeg;base64,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" alt="gym-image" width="600" height="400">

        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Your journey to a healthier life starts here. Join us and get the access to top notch equipmens experienced trainer's and variety of classes that suits your fitness goals. </p>
            <ul>
                <li>Certified personal trainers</li>
                <li>Group fitness classes</li>
                <li>Nutrition counselling</li>
                <li>State-of-art equipments</li>
            </ul>
        </section>

        <section id="schedule">
            <h2>Class Schedule</h2>
            <table>
                <caption>Weekly class schedule</caption>
                <tr>
                    <th>Day</th>
                    <th>Class</th>
                    <th>Time</th>
                    <th>Instructor</th>
                </tr>

                <tr>
                    <td>Monday</td>
                    <td>Yoga</td>
                    <th>6:00 Am - 7 Am</th>
                    <td>Parth</td>
                </tr>

                <tr>
                    <td>Tuesday</td>
                    <td>Kickboxing</td>
                    <th>6:00 Am - 7 Am</th>
                    <td>Amogh</td>
                </tr>

                <tr>
                    <td>Wednesday</td>
                    <td>Calishthenics</td>
                    <th>6:00 Am - 7 Am</th>
                    <td>Devanshi</td>
                </tr>

                <tr>
                    <td>Thursday</td>
                    <td>Calishthenics</td>
                    <th>6:00 Am - 7 Am</th>
                    <td>Devanshi</td>
                </tr>

                <tr>
                    <td>Friday</td>
                    <td>Calishthenics</td>
                    <th>6:00 Am - 7 Am</th>
                    <td>Devanshi</td>
                </tr>
            </table>

        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form action="/subit-form" method="post">
                <label for="fname">First Name: </label>
                <input type="text" id="fname" name="fname" placeholder="Enter your first name" required>
        
                <label for="lname">Last Name: </label>
                <input type="text" id="lname" name="lname" placeholder="Enter your first name" required>

                <label for="message">Message: </label>
                <textarea name="message" id="message"></textarea>
        
        
                <button type="submit">Submit</button>
            </form>
        </section>


        <aside>
            <h2>Testimonials</h2>
            <p>"Joining Ultimate Fitness Gym was the best decision i've ever made for my health. The trainer is amazing."</p>
            <p>"Joining Ultimate Fitness Gym was the best decision i've ever made for my health. The trainer is amazing."</p>
        </aside>
        <!-- <div>
            <video src=""></video>
            <audio src=""></audio>
        </div> -->
    </main>


    <footer>
        <p>&copy; 2024 Ultimate Fitness Gym  ! All Rights reserved! </p>
        <p>Visit us: 123 street Chennai 600049</p>
        <p>Follow us on social media</p>
        <nav>
            <ul>
                <li><a href="#home">Facebook</a></li>
                <li><a href="#about">Instagram</a></li>
                <li><a href="#schedule">Twitter</a></li>
            </ul>

        </nav>
    </footer>


</body>
</html>
