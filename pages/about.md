---
layout: page
title: Survey
permalink: "/about/"
---

<head>
    <title>About</title>
</head>
<body>
    <div class="container">
        This survey is coordinated by us. 
    </div>
</body>


<head>
    <title>Google Sign-In Example</title>
    
    <!-- Include the Google Sign-In library -->
    <script src="https://apis.google.com/js/platform.js" async defer></script>
</head>
<body>

<!-- Add the Sign-In button -->
<button onclick="signInWithGoogle()">Sign in with Google</button>

<script>
// Initialize the Google Sign-In API
gapi.load('auth2', function() {
    gapi.auth2.init({
        client_id: '1092513324979-i2efio0recer8vjfjsim86eva7pi7919.apps.googleusercontent.com' // Replace with your actual Client ID
    });
});

// Function to handle Google Sign-In
function signInWithGoogle() {
    gapi.auth2.getAuthInstance().signIn().then(function(googleUser) {
        // Handle the user sign-in
        console.log('User signed in.');
        // You can access user information via googleUser.getBasicProfile() and take further actions.
    });
}
</script>

</body>
