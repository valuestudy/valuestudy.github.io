---
layout: page
title: About
permalink: "/about/"
image: assets/images/screenshot.png
---
<html>
<head>
    <title>Participant Demographics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f7f7f7;
        }
        .container {
            max-width: 400px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
        }
        label, select, input {
            display: block;
            margin: 10px 0;
        }
        select, input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: #007BFF;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Participant Demographic Survey</h1>
        <form action="submit_demographics.php" method="post">
            <label for="age">Age:</label>
            <input type="text" name="age" id="age" required>

            <label for="gender">Gender:</label>
            <select name="gender" id="gender" required>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="non-binary">Non-binary</option>
                <option value="other">Other</option>
            </select>

            <label for="education">Highest Education Level:</label>
            <input type="text" name="education" id="education" required>

            <label for="occupation">Occupation:</label>
            <input type="text" name="occupation" id="occupation" required>

            <label for="income">Annual Income:</label>
            <input type="text" name="income" id="income" required>

            <label for="location">Location (City, State):</label>
            <input type="text" name="location" id="location" required>

            <label for="ethnicity">Ethnicity:</label>
            <input type="text" name="ethnicity" id="ethnicity" required>

            <label for="language">Primary Language Spoken:</label>
            <input type="text" name="language" id="language" required>

            <label for="marital-status">Marital Status:</label>
            <select name="marital-status" id="marital-status" required>
                <option value="single">Single</option>
                <option value="married">Married</option>
                <option value="divorced">Divorced</option>
                <option value="widowed">Widowed</option>
                <option value="other">Other</option>
            </select>

            <label for="children">Number of Children:</label>
            <input type="number" name="children" id="children" min="0" required>

            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>