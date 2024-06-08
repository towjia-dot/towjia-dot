<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Farzuwrixle 💌's personal website showcasing art, sketches, and book reviews.">
    <meta name="keywords" content="Farzuwrixle, art, sketches, book reviews, personal blog">
    <title>Farzuwrixle 💌's Personal Webpage</title>
    <style>
        body {
            background-color: #f2e6ff; /* Light pastel purple */
            color: #53354a; /* Dark purple */
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            overflow: auto;
            position: relative;
        }
        header {
            text-align: center;
            padding: 20px;
            background: rgba(255, 255, 255, 0.7); /* Semi-transparent white */
            border: 1px solid #53354a; /* Dark purple */
            border-radius: 10px;
            width: 90%;
            margin-top: 20px;
            position: relative; /* for positioning the text art */
        }
        h1 {
            font-size: 3em;
            color: #53354a; /* Dark purple */
            position: relative;
            display: inline-block;
        }
        .bio {
            font-size: 1.2em;
            margin-top: 10px;
            font-style: italic;
        }
        section {
            margin: 20px 0;
            width: 90%;
            text-align: center;
        }
        .content {
            margin: 10px;
            padding: 10px;
            background: rgba(255, 255, 255, 0.7); /* Semi-transparent white */
            border: 1px solid #53354a; /* Dark purple */
            border-radius: 10px;
            transition: transform 0.3s, background 0.3s;
        }
        .content:hover {
            transform: scale(1.05);
            background: rgba(255, 255, 255, 0.9); /* More opaque white */
        }
        .content h3, .content h2 {
            margin: 0;
            color: #53354a; /* Dark purple */
        }
        .content p, .content a {
            margin-top: 5px;
            color: #53354a; /* Dark purple */
        }
        .gallery img {
            width: 100%;
            height: auto;
            max-width: 300px;
        }
    </style>
</head>
<body>
    <header>
        <h1>
            Farzuwrixle 💌
        </h1>
        <p class="bio">
            ヾ(❀╹◡╹)ﾉﾞ~✉️ Beep..! One massage ˎˊ˗<br>
            ⌨️ zzZ  [ Farzuwrixle💌 ] is typing ... ᰔᩚ<br>
            ˚ ༘♡ ·˚꒰ᥕᥱᥣᥴ᥆꧑ᥱ t᥆ ꧑ᥡ bᥣ᥆g꒱ ིྀᰔ
        </p>
    </header>
    <section class="projects">
        <div class="content">
            <h3>Art and Sketching Portfolio</h3>
            <p>This project showcases my passion for art and sketching. It includes a collection of my sketches, highlighting various styles and techniques I have explored over the years. The portfolio is designed to be visually appealing with a vintage touch and includes animated transitions to enhance the viewing experience. Technologies used include HTML, CSS, and JavaScript. Future plans involve adding a blog section where I share tips and tutorials on sketching.</p>
        </div>
        <div class="content">
            <h3>Book Reviews and Recommendations</h3>
            <p>This project is dedicated to my love for reading. It features detailed reviews of books I have read, along with my personal recommendations. The site is designed to be user-friendly with a vintage aesthetic, and includes animations to make the content more engaging. Technologies used include HTML, CSS, and JavaScript. Future plans include adding a forum for book discussions and a feature for users to submit their own reviews.</p>
        </div>
    </section>
    <section class="blog">
        <h2>Blog Posts</h2>
        <div class="content">
            <h3>My First Blog Post</h3>
            <p>Content of the first blog post goes here...</p>
        </div>
        <div class="content">
            <h3>Another Interesting Topic</h3>
            <p>Content of another blog post goes here...</p>
        </div>
    </section>
    <section class="gallery">
        <h2>My Sketches</h2>
        <div class="content">
            <img src="path/to/your/image1.jpg" alt="Sketch 1">
        </div>
        <div class="content">
            <img src="path/to/your/image2.jpg" alt="Sketch 2">
        </div>
    </section>
    <section class="videos">
        <h2>Videos</h2>
        <div class="content">
            <video controls>
                <source src="path/to/your/video1.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <div class="content">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/video_id" frameborder="0" allowfullscreen></iframe>
        </div>
    </section>
    <section class="links">
        <h2>Useful Links</h2>
        <div class="content">
            <a href="https://www.example.com">Visit Example.com</a>
        </div>
        <div class="content">
            <a href="https://www.another-example.com">Visit Another Example.com</a>
        </div>
    </section>
</body>
</html>
