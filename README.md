<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Page</title>
</head>
<body>

    <h1>Multimedia Webpage</h1>

    <!-- Audio Element -->
    <h2>Audio Example</h2>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Video Element -->
    <h2>Video Example</h2>
    <video controls width="400">
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</body>
</html>
<h2>Registration Form</h2>
<form>
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" minlength="6" required><br><br>

    <button type="submit">Register</button>
</form>
<h2>Embedded Image</h2>
<img src="image.jpg" alt="Sample Image" width="300">
<h2>Sample Table</h2>
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>25</td>
    </tr>
    <tr>
        <td>Bob</td>
        <td>30</td>
    </tr>
</table>
<h2>Favorite Programming Languages</h2>
<ul>
    <li>Python</li>
    <li>JavaScript</li>
    <li>HTML & CSS</li>
</ul>
