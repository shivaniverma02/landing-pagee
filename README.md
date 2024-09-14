<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Product</h1>
        <p>Your one-stop solution for [your service or product]</p>
    </header>
    
    <section class="cta">
        <h2>Join Us Today!</h2>
        <p>Sign up now and enjoy a 30-day free trial.</p>
        <button>Get Started</button>
    </section>

    <section class="features">
        <h2>Our Features</h2>
        <div class="feature">
            <h3>Feature 1</h3>
            <p>Details about feature 1.</p>
        </div>
        <div class="feature">
            <h3>Feature 2</h3>
            <p>Details about feature 2.</p>
        </div>
        <div class="feature">
            <h3>Feature 3</h3>
            <p>Details about feature 3.</p>
        </div>
    </section>

    <footer>
        <p>© 2024 Your Company</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0 20px;
}

header {
    text-align: center;
    margin-top: 50px;
}

h1 {
    font-size: 2.5rem;
}

p {
    font-size: 1.2rem;
    margin-top: 10px;
}

.cta {
    background-color: #007BFF;
    color: white;
    padding: 20px;
    margin-top: 50px;
    text-align: center;
}

.cta button {
    background-color: #0056b3;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1.2rem;
    cursor: pointer;
    border-radius: 5px;
}

.features {
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
    width: 100%;
    max-width: 900px;
}

.feature {
    flex: 1;
    background-color: white;
    padding: 20px;
    margin: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

footer {
    margin-top: 50px;
    text-align: center;
}
