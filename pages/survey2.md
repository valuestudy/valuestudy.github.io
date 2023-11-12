---
layout: page
title: Survey2
permalink: "/survey2/"
---


<body>
     We ask you here another set of questions.
    <form action="success.html" method="post" style="max-width: 400px; margin: 0 auto; text-align: left;">
        <div style="margin: 10px 0;">
            <label for="age" style="display: block; margin-bottom: 5px;">Age:</label>
            <input type="text" name="age" id="age" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px;">
        </div>

        <div style="margin: 10px 0;">
            <label for="privacy" style="display: block; margin-bottom: 5px;">privacy preference:</label>
            <select name="privacy" id="privacy" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px;">
                <option value="male">Care</option>
                <option value="female">Not caring</option>
            </select>
        </div>

        <!-- Add more form fields here -->

        <div style="text-align: center; margin-top: 20px;">
            <input type="submit" value="Submit" style="background-color: #007BFF; color: #fff; border: none; padding: 10px 20px; cursor: pointer; border-radius: 5px;">
        </div>
    </form>
</body>
