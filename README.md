# oibsip_taskno.1
Landing page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Landing Page</title>
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
    </header>

    <section class="features">
        <div class="feature">
            <h2>Feature 1</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="feature">
            <h2>Feature 2</h2>
            <p>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
        <div class="feature">
            <h2>Feature 3</h2>
            <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.</p>
        </div>
    </section>

    <section class="call-to-action">
        <h2>Get Started Today</h2>
        <p>Sign up now and enjoy our amazing services.</p>
        <a href="#" class="btn">Sign Up</a>
    </section>

    <footer>
        <p>&copy; 2023 Your Company</p>
    </footer>
</body>
</html>




/* Reset some default styles */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

/* Apply a background color and basic styles to the header */
header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

/* Create columns for the feature section */
.features {
    display: flex;
    justify-content: space-around;
    padding: 40px;
}

/* Style individual feature items */
.feature {
    text-align: center;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

/* Style the call-to-action section */
.call-to-action {
    background-color: #f8f8f8;
    text-align: center;
    padding: 40px;
}

/* Style the button */
.btn {
    display: inline-block;
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #555;
}

/* Style the footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
