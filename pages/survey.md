---
layout: page
title: Survey
permalink: "/survey/"
---

<head>
    <title>Participant Demographics</title>
</head>
<body>
    <div class="container">
            Please answer the following questions. 
        <form action="submit_demographics.php" method="post">
            <label for="age">Age:</label>
            <input type="text" name="age" id="age" required><br>

            <label for="gender">Gender:</label>
            <select name="gender" id="gender" required>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="non-binary">Non-binary</option>
                <option value="other">Other</option>
            </select><br>

            <label for="education">Highest Education Level:</label>
            <input type="text" name="education" id="education" required><br>

            <!-- Add more form fields here -->

            <input type="submit" value="Submit">
        </form>
    </div>
</body>
