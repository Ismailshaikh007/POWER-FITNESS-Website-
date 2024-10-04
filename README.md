<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE Gym</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('gym-bg.jpg') no-repeat center center fixed;
            background-size: cover;
            color: black; /* Changed text color to black */
        }
        header {
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: black;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        header img {
            width: 100px; /* Adjust the size as needed */
            margin-right: 20px;
        }
        nav {
            background-color: rgba(0, 0, 0, 0.7);
            overflow: hidden;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color:  #ddd;
            color: black;
        }
        .hero {
            background: rgba(0, 0, 0, 0.7);
            height: 400px;
            text-align: center;
            color: white;
            padding-top: 150px;
            background-image: url("bg.jpg");
            background-repeat: no-repeat;
            background-size: 100%;
        }
        .hero h1 {
            font-size: 3em;
        }
        .content {
            position: relative;
            left: 0%;
            padding: 20px;
            color: black; /* Black text for content */
        }
        .trainer {
            margin: 0 auto;
            max-width: 1200px;
            text-align: center;
        }
        .trainer img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .trainer-info {
            margin: 20px;
        }
        .gym-machines, .attitude, .membership, .testimonials {
            background-color: rgba(255, 255, 255, 0.8); /* Light background for black text readability */
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            color: black; /* Black text */
        }
        .footer {
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            text-align: center;
            padding: 10px;
        }
        .machine-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }
        .machine-gallery .xyz {
            text-align: center;
            width: 150px; /* Consistent width for each gallery item */
        }
        .machine-gallery img {
            width: 100%;  /* Ensure the image fills the .xyz container */
            height: 140px;
            border-radius: 10px;
            object-fit: cover; /* Fit the image without distortion */
        }
        .quote {
            font-style: italic;
            font-size: 1.5em;
            color: black; /* Black for quotes */
        }
        .trainer-info, .trainer {
            height: 450px;
            width: 120px;
            display: inline-block;
            padding: 20px;
        }
        .xyz {
            height: 400px;
            width: 300px;
            display: inline-block;
        }
        .main {
            height: 300px;
            width: 800px;
            position: relative;
            left: 10%;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
        }
        table {
            width: 50%;
            margin: 0 auto;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
        }
        input, select, textarea {
            width: 100%;
            height: 40px;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }
        textarea {
            height: 80px;
            resize: vertical;
        }
        select {
            height: 40px;
        }
        .submit-btn {
            background-color:  grey;
            color: white;
            border: none;
            padding: 15px;
            width: 200px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .submit-btn:hover {
            background-color: black;
        }
        td {
            color: white;
            padding: 10px;
        }
        tr{
        color: black;
        margin:5px;
        }
        
    </style>
</head>
<body>

<header>
    <img src="power fitness logo.webp" alt="Gym Logo">
    <h1>"POWER FITNESS"</h1>
</header>

<nav>
    <a href="#home">Home.</a>
    <a href="#about">About Us.</a>
    <a href="#machines">Machines.</a>
    <a href="#trainers">Trainers.</a>
    <a href="#membership">Monthly Plan.</a>
    <a href="#contact">Contact.</a>
</nav>

<section id="home" class="hero">
    <div class="main">
        <h1>Welcome to "POWER FITNESS"</h1>
        <p>Your journey to fitness starts here!</p>
    </div>
</section>

<section id="about" class="content" align="left">
    <h2>About Us</h2>
    <p>"POWER FITNESS" is dedicated to helping you achieve your fitness goals with top-class equipment, certified trainers, and a variety of fitness programs.</p>

</section>

<section id="machines" class="gym-machines">
    <h2>Our Gym Machines</h2>
    <div class="machine-gallery">
        <div class="xyz">
            <img src="treadmill.jpeg" alt="Treadmill">
            <p>Treadmill</p>
        </div>
        <div class="xyz">
            <img src="weight.jpg" alt="Weights">
            <p>Weights</p>
        </div>
        <div class="xyz">
            <img src="elliptical.jpg" alt="Elliptical">
            <p>Elliptical</p>
        </div>
        <div class="xyz">
            <img src="bench press.jpg" alt="Bench Press">
            <p>Bench Press</p>
        </div>
        <div class="xyz">
            <img src="LegPress.jpg" alt="Leg Press">
            <p>Leg Press</p>
        </div>
    </div>
</section>

<section id="trainers" class="content">
    <h2>Meet Our Trainers</h2>
    <div class="trainer-info trainer">
        <img src="sandip.jpg" alt="Sandip">
        <p><strong>Sandip:</strong> Strength training expert with 5 years of experience.</p>
    </div>
    <div class="trainer-info trainer">
        <img src="kuldip.webp" alt="Kuldip">
        <p><strong>Kuldip:</strong> Cardio and endurance specialist, ensures you're always pushing your limits.</p>
    </div>
    <div class="trainer-info trainer">
        <img src="anish.jpg" alt="Anish">
        <p><strong>Anish:</strong> HIIT and flexibility trainer, helps you gain agility and power.</p>
    </div>
    <div class="trainer-info trainer">
        <img src="pooja.jpg" alt="Pooja">
        <p><strong>Pooja:</strong> Yoga and Pilates expert, creating balance between mind and body.</p>
    </div>
    
</section>

<section id="attitude" class="attitude">
    <h2>Motivated Snowgen</h2>
    <p class="quote">"Leave your excuses at the door, because at "POWER FITNESS", we turn sweat into success."</p>
    <p class="quote">"Train insane or remain the same."</p>
        <p class="quote">"Your fitness is 100% mental. Your body won’t go where your mind doesn’t push it."</p>
</section>

<section id="membership" class="membership" align="center">
    <h2>Membership Plans</h2>
    <table>
        <tr>
            <td>Plan</td>
            <td>Duration</td>
            <td>Price</td>
            <td>Feature</td>
        </tr>
        <tr>
            <td>Basic</td>
            <td>1 Month</td>
            <td>800₹</td>
            <td>Full access to gym equipment
1 group fitness class per week
Locker access
General fitness consultation
Flexible gym timings (limited to non-peak hours)
No personal trainer or advanced amenities</td>
        </tr>
        <tr>
            <td>Standard</td>
            <td>3 Months</td>
            <td>2300₹</td>
            <td>All Basic Plan features
3 group fitness classes per week
Access to more advanced machines (e.g., HIIT, resistance machines)
1 personalized fitness consultation per month
Priority access during non-peak hours
Complimentary towel service</td>
        </tr>
        <tr>
            <td>Premium</td>
            <td>6 Months</td>
            <td>4500₹</td>
            <td>All Standard Plan features
Unlimited group fitness classes
1 personal trainer session per month
Customized fitness and nutrition plan
Access to steam room, sauna, and premium machines
2 guest passes per month for friends or family
Free Wi-Fi access in the gym</td>
        </tr>
        <tr>
            <td>VIP</td>
            <td>1 Years</td>
            <td>8500₹</td>
            <td>All Premium Plan features
Unlimited personal trainer sessions
Personalized fitness coaching (workout + diet plan)
Exclusive access to VIP locker rooms and showers
Complimentary sports drinks and protein shakes
Monthly fitness assessments (BMI, muscle mass, etc.)
Priority registration for new classes and gym events
Access to VIP lounge and reserved parking
Complimentary gym apparel kit (shirts, bottles, etc.)</td>
        </tr>
    </table>
</section>

<section id="testimonials" class="testimonials">
    <h2>What Our Members Say</h2>
    <p class="quote">"Joining "POWER FITNESS" was the best decision I made for my health. The trainers are amazing, and the machines are top-notch!" - Sarah M.</p>
    <p class="quote">"I've never felt more energized and motivated. The atmosphere at "POWER FITNESS" pushes you to do your best." - John D.</p>
    <p class="quote">"The yoga classes have really helped me achieve balance in my life, both physically and mentally." - Priya S.</p>
</section>

<section id="contact" class="content">
    <h2>Contact Us</h2>
    <form action="submit_form.php" method="post">
        <table>
            <tr>
                <td><label for="name">Name:</label></td>
                <td><input type="text" id="name" name="name" placeholder="Your full name" required></td>
            </tr>
            <tr>
                <td><label for="email">Email:</label></td>
                <td><input type="email" id="email" name="email" placeholder="Your email" required></td>
            </tr>
            <tr>
                <td><label for="phone">Phone:</label></td>
                <td><input type="tel" id="phone" name="phone" placeholder="Your phone number"></td>
            </tr>
            <tr>
                <td><label for="plan">Membership Plan:</label></td>
                <td>
                    <select id="plan" name="plan">
                        <option value="basic">Basic (1 Month)</option>
                        <option value="standard">Standard (3 Months)</option>
                        <option value="premium">Premium (6 Months)</option>
                        <option value="vip">VIP (1 Years)</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td><label for="message">Message:</label></td>
                <td><textarea id="message" name="message" placeholder="Any questions or comments"></textarea></td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <input type="submit" class="submit-btn" value="Submit">
                </td>
            </tr>
        </table>
    </form>
</section>

<footer class="footer">
    <p>&copy; 2024 "POWER FITNESS". All rights reserved.</p>
</footer>

</body>
</html>
