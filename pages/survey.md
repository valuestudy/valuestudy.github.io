---
layout: page
title: Survey
permalink: "/survey/"
---

<head>
    <title>Participant Demographics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f7f7f7;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
        }
        .form-group {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin: 10px 0;
        }
        label {
            width: 45%; /* Adjust the width as needed */
            text-align: left;
        }
        input, select {
            width: 50%; /* Adjust the width as needed */
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
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="text" name="age" id="age" required>
            </div>
            <div class="form-group">
                <label for="gender">Gender:</label>
                <select name="gender" id="gender" required>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="non-binary">Non-binary</option>
                    <option value="other">Other</option>
                </select>
            </div>
            <!-- Add more form fields here -->
            <div class="form-group">
                <label for="children">Number of Children:</label>
                <input type="number" name="children" id="children" min="0" required>
            </div>
            <input type="submit" value="Submit">
        </form>
    </div>
</body>