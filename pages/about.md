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


<script src="https://apis.google.com/js/platform.js" async defer></script>

<meta name="google-signin-client_id" content="1092513324979-i2efio0recer8vjfjsim86eva7pi7919.apps.googleusercontent.com">

<div class="g-signin2" data-onsuccess="onSignIn"></div>


<!-- Add the Sign-In button -->
<button onclick="google-signin-button" data-clientid="1092513324979-i2efio0recer8vjfjsim86eva7pi7919.apps.googleusercontent.com">Sign in with Google</button>

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

// Attach the signInWithGoogle function to the button's click event
document.getElementById('google-signin-button').addEventListener('click', signInWithGoogle);
</script>
