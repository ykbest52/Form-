<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Signup Page</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<div class="container">

<div class="left">
<h1>Empowering the <span>Future</span> of Electric Mobility</h1>
<p>Next-generation OCPP compliant management software.</p>
</div>

<div class="right">

<h2>Get started</h2>

<form id="signupForm">

<label>Full Name</label>
<input type="text" id="name" placeholder="Enter your full name">

<label>Email Address</label>
<input type="email" id="email" placeholder="work@company.com">

<label>Create Password</label>
<input type="password" id="password">

<div class="strength-bar">
<div id="strength"></div>
</div>

<label>Confirm Password</label>
<input type="password" id="confirm">

<button type="submit">Create Account</button>

</form>

</div>

</div>

<script src="script.js"></script>

</body>
</html>
