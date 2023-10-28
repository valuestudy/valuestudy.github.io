---
layout: page
title: Survey
permalink: "/survey/"
---


<head>
    <title>Participant Demographics</title>
</head>
<body>
    <h1 style="text-align: center;">Participant Demographic Survey</h1>
    <form action="submit_demographics.php" method="post" style="max-width: 400px; margin: 0 auto; text-align: left;">
        <div style="margin: 10px 0;">
            <label for="age" style="display: block; margin-bottom: 5px;">Age:</label>
            <input type="text" name="age" id="age" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px;">
        </div>

        <div style="margin: 10px 0;">
            <label for="gender" style="display: block; margin-bottom: 5px;">Gender:</label>
            <select name="gender" id="gender" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px;">
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="non-binary">Non-binary</option>
                <option value="other">Other</option>
            </select>
        </div>

        <!-- Add more form fields here -->

        <input type="submit" value="Submit" style="background-color: #007BFF; color: #fff; border: none; padding: 10px 20px; cursor: pointer; border-radius: 5px;">
    </form>
</body>
