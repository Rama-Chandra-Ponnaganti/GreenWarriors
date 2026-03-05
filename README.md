# GreenWarriors
<!DOCTYPE html>
<html>
<head>
    <title>Green Warriors</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f0fff4;
        }

        header {
            background: #2e8b57;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background: #228b22;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 15px;
        }

        h2 {
            color: #2e8b57;
        }

        .card {
            background: white;
            padding: 15px;
            margin: 10px 0;
            border-radius: 10px;
            box-shadow: 0 0 8px rgba(0,0,0,0.1);
        }

        img {
            width: 100%;
            max-width: 400px;
            border-radius: 10px;
        }

        button {
            background: #2e8b57;
            color: white;
            padding: 10px;
            border: none;
            width: 100%;
            border-radius: 5px;
        }

        footer {
            background: #2e8b57;
            color: white;
            text-align: center;
            padding: 10px;
        }

        @media (min-width: 768px) {
            .container {
                display: flex;
                gap: 20px;
            }
            .card {
                flex: 1;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>🌿 Green Warriors 🌿</h1>
    <p>Balancing Devotion & Ecology</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#telugu">తెలుగు</a>
    <a href="#gallery">Gallery</a>
    <a href="#join">Join</a>
</nav>

<section id="about">
    <h2>About Us</h2>
    <div class="card">
        Green Warriors is a youth initiative teaching Vishnu Sahasranamam and spreading ecology awareness.
    </div>
</section>

<section id="telugu">
    <h2>తెలుగు విభాగం</h2>
    <div class="card">
        గ్రీన్ వారియర్స్ ప్రకృతి పరిరక్షణ మరియు భక్తి విద్యను ఉచితంగా అందించే సమూహం.
    </div>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <div class="card">
        <img src="tree.jpg">
        <p>Upload your images to GitHub repository.</p>
    </div>
</section>

<section id="join">
    <h2>Join Green Warriors</h2>
    <div class="card">
        <input type="text" placeholder="Your Name">
        <br><br>
        <input type="email" placeholder="Your Email">
        <br><br>
        <button>Register</button>
    </div>
</section>

<footer>
    © 2026 Green Warriors | Made with 💚
</footer>

</body>
</html>
<a href="#register">Register</a><nav>
    <a href="#about">About</a>
    <a href="#activities">Activities</a>
    <a href="#poetry">Poetry</a>
    <a href="#contact">Contact</a>
    <a href="#register">Register</a>
</nav><section id="register">
    <h2>Join Green Warriors</h2>
    <div class="card">
        <form>
            <label>Name:</label><br>
            <input type="text" placeholder="Enter your name" required><br><br>

            <label>Email:</label><br>
            <input type="email" placeholder="Enter your email" required><br><br>

            <label>Why do you want to join?</label><br>
            <textarea placeholder="Write your message"></textarea><br><br>

            <button type="submit">Register</button>
        </form>
    </div>
</section>input, textarea {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
}

button {
    background-color: #2e8b57;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}u
