<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 week 2 assignment</title>
</head>

<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Webpage</h1>
        <p>This webpage includes multimedia elements, a form, a table, and more!</p>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>My Top 5 Favorite Movies (Roman Numerals)</h2>
        <ol type="I">
            <li>The Shawshank Redemption</li>
            <li>The Godfather</li>
            <li>The Dark Knight</li>
            <li>Forrest Gump</li>
            <li>Inception</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Beautiful Nature</h2>
        <img src="https://images.pexels.com/photos/457882/pexels-photo-457882.jpeg" alt="Nature" width="600">
    </section>

    <!-- Table of 5 Contacts -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Elm St, Cityville</td>
                <td>555-1234</td>
                <td>johndoe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak St, Townsville</td>
                <td>555-5678</td>
                <td>janesmith@example.com</td>
            </tr>
            <tr>
                <td>Mary Johnson</td>
                <td>789 Pine St, Village</td>
                <td>555-8765</td>
                <td>maryj@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>101 Maple St, Smalltown</td>
                <td>555-4321</td>
                <td>michaelb@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>202 Birch St, Uptown</td>
                <td>555-6789</td>
                <td>emilyd@example.com</td>
            </tr>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="/submit" method="post">
            <!-- Name -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <!-- Email -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <!-- Password -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <!-- Date -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select a country</option>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="india">India</option>
                <option value="australia">Australia</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <!-- Checkboxes -->
            <label>Interests:</label><br>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label><br><br>

            <!-- Submit Button -->
            <button type="submit">Submit</button>
        </form>
    </section>

    <!-- Audio Element -->
    <section>
        <h2>Audio Player</h2>
        <audio controls>
            <source src="audiofile.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
    </section>

    <!-- Video Element -->
    <section>
        <h2>Video Player</h2>
        <video controls width="600">
            <source src="videofile.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

</body>

</html>
