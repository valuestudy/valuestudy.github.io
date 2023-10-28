---
layout: page
title: About
permalink: "/about/"
image: assets/images/screenshot.png
---

<html>
<head>
    <title>Participant Demographics</title>
</head>

<body>
<div class="container">
    <h1>Participant Demographic Survey</h1>
    <form action="submit_demographics.php" method="post">
        <label for="age">1. Age:</label>
        <input type="text" name="age" id="age" required><br>

        <label for="gender">2. Gender:</label>
        <select name="gender" id="gender" required>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="non-binary">Non-binary</option>
            <option value="other">Other</option>
        </select><br>

        <label for="education">3. Highest Education Level:</label>
        <input type="text" name="education" id="education" required><br>

        <label for="occupation">4. Occupation:</label>
        <input type="text" name="occupation" id="occupation" required><br>

        <label for="income">5. Annual Income:</label>
        <input type="text" name="income" id="income" required><br>

        <label for="location">6. Location (City, State):</label>
        <input type="text" name="location" id="location" required><br>

        <label for="ethnicity">7. Ethnicity:</label>
        <input type="text" name="ethnicity" id="ethnicity" required><br>

        <label for="language">8. Primary Language Spoken:</label>
        <input type="text" name="language" id="language" required><br>

        <label for="marital-status">9. Marital Status:</label>
        <select name="marital-status" id="marital-status" required>
            <option value="single">Single</option>
            <option value="married">Married</option>
            <option value="divorced">Divorced</option>
            <option value="widowed">Widowed</option>
            <option value="other">Other</option>
        </select><br>

        <label for="children">10. Number of Children:</label>
        <input type="number" name="children" id="children" min="0" required><br>

        <input type="submit" value="Submit">
    </form>
</div>
</body>
</html>
