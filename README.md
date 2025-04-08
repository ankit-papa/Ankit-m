
<!DOCTYPE html
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankit's Website</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5f5f5;
            color: #333;
        }

        header {
            background: linear-gradient(45deg, #ff7e5f, #feb47b);
            color: white;
            text-align: center;
            padding: 60px 0;
        }

        header h1 {
            font-size: 50px;
            margin: 0;
        }

        header p {
            font-size: 20px;
            margin-top: 10px;
        }

        .main-container {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            margin-top: 40px;
        }

        .content .card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex: 1;
            margin: 20px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .content .card:hover {
            transform: translateY(-10px);
        }

        .btn {
            background-color: #ff7e5f;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            text-transform: uppercase;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #feb47b;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

    </style>
</head>

<body>

    <header>
        <h1>Welcome to Ankit's Website</h1>
        <p>I'm a passionate web designer, 17 years old, and studying in 12th class.</p>
    </header>

    <div class="main-container">

        <section class="content">
            <div class="card">
                <h2>About Me</h2>
                <p>I'm learning web design and creating stunning websites for businesses and personal projects. I aim to become an expert and master front-end development.</p>
                <button class="btn">Learn More</button>
            </div>
            <div class="card">
                <h2>My Projects</h2>
                <p>Check out my projects, where I showcase different web design and development work that I've done.</p>
                <button class="btn">View Projects</button>
            </div>
            <div class="card">
                <h2>Contact Me</h2>
                <p>If you're interested in collaborating or have any questions, feel free to get in touch with me!</p>
                <button class="btn">Contact</button>
            </div>
        </section>

</body>

</html>
