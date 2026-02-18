<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ansh | Portfolio</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">
.
    <h1 class="name">Ansh</h1>
    <p class="intro">Student | Learner | Explorer</p>
.
    <div class="card">
        <h2>About Me</h2>
        <p>Hi! I enjoy learning new things, reading manga & manhwa, and building my skills every day.</p>
    </div>
.
    <div class="card">
        <h2>Hobbies</h2>
        <ul>
            <li>Reading Manga & Manhwa</li>
            <li>Learning Coding</li>
            <li>Fitness & Gym</li>
        </ul>
    </div>
.
    <div class="card">
        <h2>School</h2>
        <p>Pride International School, Narkatiaganj, Bihar<br>English Medium | AC | Digital Board</p>
    </div>
.
    <div class="buttons">
        <a href="about.html" class="btn">Know more about me</a>
        <a href="index.html" class="btn">Back to Home</a>
    </div>

</div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ansh | About</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
.
    <h1 class="name">About Me</h1>
    <p class="intro">Hi! I am Ansh, a student who loves learning, reading manga & manhwa, and building skills every day.</p>
.
    <div class="card">
        <h2>My Hobbies</h2>
        <ul>
            <li>Reading Manga & Manhwa</li>
            <li>Learning Coding</li>
            <li>Fitness & Gym</li>
        </ul>
    </div>
.
    <div class="card">
        <h2>My School</h2>
        <p>Pride International School, Narkatiaganj, Bihar<br>English Medium | AC | Digital Board</p>
    </div>
.
    <div class="buttons">
        <a href="index.html" class="btn">🏠 Back to Home</a>
    </div>

</div>

</body>
</html>
/* Font & Body */
body {
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(to right, #4facfe, #00f2fe);
    color: #fff;
    margin: 0;
    padding: 0;
}

/* Container */
.container {
    max-width: 900px;
    margin: 50px auto;
    padding: 40px;
    background: rgba(0,0,0,0.6);
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.7);
}

/* Name */
.name {
    font-size: 55px;
    margin-bottom: 10px;
    font-weight: 700;
}

/* Intro */
.intro {
    font-size: 18px;
    margin-bottom: 30px;
}

/* Card Style */
.card {
    background: rgba(255,255,255,0.1);
    padding: 25px;
    margin: 20px 0;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.4);
    transition: transform 0.3s ease, background 0.3s ease;
}

.card:hover {
    transform: translateY(-5px);
    background: rgba(255,255,255,0.2);
}

/* Card Headings */
.card h2 {
    font-size: 28px;
    margin-bottom: 15px;
    text-decoration: underline;
    text-underline-offset: 6px;
}

/* Lists */
ul {
    text-align: left;
    display: inline-block;
    list-style-type: square;
}

/* Buttons */
.buttons {
    margin-top: 30px;
}

.btn {
    display: inline-block;
    padding: 12px 25px;
    margin: 10px;
    background: #fffa65;
    color: #000;
    font-weight: 600;
    border-radius: 12px;
    text-decoration: none;
    transition: background 0.3s, transform 0.3s;
}

.btn:hover {
    background: #ffd700;
    transform: scale(1.1);
}

/* Responsive */
@media (max-width: 600px) {
    .container {
        padding: 20px;
        margin: 20px;
    }
    .name {
        font-size: 40px;
    }
    .card h2 {
        font-size: 22px;
    }
}

</body>
</html>

