---
layout: page
title: Survey
permalink: "/survey/"
---


<body>
     We kindly request that you answer the survey questions with honesty and candor. Your genuine responses are essential for the success and accuracy of our research. Your anonymity and privacy will be respected throughout the process.
    <form action="success.html" method="post" style="max-width: 400px; margin: 0 auto; text-align: left;">
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
            <!-- Internet Usage -->
        <fieldset>
            <legend>2. Internet Usage</legend>
            <label>
                How many hours do you spend online per day?
                <input type="number" name="hours_online" min="0" max="24">
            </label>
            <br>
            <label>
                What is your primary purpose for using the internet?
                <input type="text" name="internet_purpose">
            </label>
        </fieldset>
        <!-- Web Browsers -->
        <fieldset>
            <legend>3. Web Browser Usage</legend>
            <label>
                Which web browser do you primarily use?
                <select name="web_browser">
                    <option value="brave">Brave</option>
                    <option value="chrome">Chrome</option>
                    <option value="firefox">Firefox</option>
                    <option value="safari">Safari</option>
                    <option value="other">Other</option>
                </select>
            </label>
        </fieldset>
        </div>

        <!-- Add more form fields here -->

        <div style="text-align: center; margin-top: 20px;">
            <input type="submit" value="Submit" style="background-color: #007BFF; color: #fff; border: none; padding: 10px 20px; cursor: pointer; border-radius: 5px;">
        </div>
    </form>
</body>
