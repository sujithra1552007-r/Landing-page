# Landing-page
A landing page in web development is a single web page designed to capture user attention and encourage a specific action. It uses simple design, clear content, and attractive visuals to engage visitors effectively.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Landing Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Header */
        header {
            background: #3e8da2;
            color: rgb(246, 237, 237);
            padding: 15px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #5aabb1;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(to right, #2abee7, #3cdbf0);
            color: white;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero h1 {
            font-size: 40px;
        }

        .hero p {
            margin: 15px 0;
        }

        .btn {
            background: white;
            color: #2196f3;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-weight: bold;
            border-radius: 5px;
        }

        .btn:hover {
            background: #f1f1f1;
        }

        /* Features Section */
        .features {
            display: flex;
            justify-content: space-around;
            padding: 40px;
            background: #f4f4f4;
        }

        .box {
            background: white;
            padding: 20px;
            width: 30%;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h2>My Landing Page</h2>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to My Website</h1>
        <p>Create beautiful websites with HTML & CSS</p>
        <button class="btn">Get Started</button>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="box">
            <h3>Easy Design</h3>
            <p>Simple and clean layout for beginners.</p>
        </div>

        <div class="box">
            <h3>Responsive</h3>
            <p>Works well on all screen sizes.</p>
        </div>

        <div class="box">
            <h3>Creative</h3>
            <p>Customize colors and styles easily.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 My Landing Page | All Rights Reserved</p>
    </footer>

</body>
</html>
