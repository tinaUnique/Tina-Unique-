my-ink-brand-site/ 
</style>
</head>
<body>
<h1>Contact Tina Unique</h1>

<form action="mailto:your-email@example.com" method="post" enctype="text/plain">
<label for="name">Name</label>
<input id="name" name="name" type="text" required />

<label for="email">Email</label>
<input id="email" name="email" type="email" required />

<label for="message">Message</label>
<textarea id="message" name="message" required></textarea>

<button type="submit">Send</button>
</form>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Books by Tina Unique</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Merriweather:wght@400;700&family=Montserrat:wght@700&display=swap');

body {
background-color: #0A0A0A;
color: #fff;
font-family: 'Merriweather', serif;
max-width: 900px;
margin: 2rem auto;
padding: 1rem;
line-height: 1.7;
}

h1 {
font-family: 'Great Vibes', cursive;
color: #D4AF37;
font-size: 3rem;
text-align: center;
margin-bottom: 2rem;
}

.book {
background: #111111;
border-left: 6px solid #D4AF37;
padding: 1.5rem;
margin-bottom: 2rem;
box-shadow: 0 0 10px rgba(212, 175, 55, 0.3);
}

h2 {
color: #E9C874;
font-family: 'Montserrat', sans-serif;
margin-top: 0;
}

p {
color: #ddd;
font-size: 1.1rem;
margin-bottom: 1rem;
}

.buy-btn {
display: inline-block;
background-color: #FF4FA8;
color: white;
padding: 0.75rem 1.5rem;
font-weight: 700;
font-family: 'Montserrat', sans-serif;
border-radius: 30px;
text-decoration: none;
transition: background-color 0.3s ease;
}

.buy-btn:hover {
background-color: #D43E85;
}
</style>
</head>
<body>
<h1>Books by Tina Unique</h1>

<div class="book">
<h2>Becoming a Mother at 17</h2>
<p>My journey of strength, resilience, and love, making it to 42 unscathed despite the hardships.</p>
<a href="#" class="buy-btn" target="_blank" rel="noopener noreferrer">Buy on Amazon</a>
</div>

<div class="book">
<h2>Legendary</h2>
<p>Triumphing over trials and tribulations to stay on top and ahead of the game — proving I’m never behind.</p>
<a href="#" class="buy-btn" target="_blank" rel="noopener noreferrer">Buy on Amazon</a>
</div>
</body>
</html>



About Page (about.html)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>About Tina Unique</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Merriweather:wght@400;700&family=Montserrat:wght@700&display=swap');

body {
background-color: #0A0A0A;
color: #fff;
font-family: 'Merriweather', serif;
max-width: 900px;
margin: 2rem auto;
padding: 1rem;
line-height: 1.7;
}

h1 {
font-family: 'Great Vibes', cursive;
color: #D4AF37;
font-size: 3rem;
text-align: center;
margin-bottom: 1rem;
}

p {
font-size: 1.1rem;
color: #ddd;
margin-bottom: 1rem;
}

strong {
color: #E9C874;
}

a {
color: #FF4FA8;
text-decoration: none;
font-weight: 700;
}

a:hover {
text-decoration: underline;
}
</style>
</head>
<body>
<h1>About Tina Unique</h1>
<p><strong>Tina Unique</strong> is a bold, beautiful, and powerful author whose memoirs chronicle her remarkable journey. Becoming a mother at 17, Tina faced life's challenges head-on and made it to 42 unscathed — a testament to her strength and resilience.</p>
<p>Her second memoir tells the story of her legendary rise above trials and tribulations, proving she's always ahead of the game, never behind. Tina’s voice is elegant with a slight dramatic flair, embodying creativity and uniqueness.</p>
<p>In addition to her writing, Tina collaborates with InkWorld Publishing, bringing her artistic vision to a wider audience.</p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Tina Unique | Author</title>
<style>
/* Base Reset & Fonts */
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Merriweather:wght@400;700&family=Montserrat:wght@700&display=swap');

body {
margin: 0;
background-color: #0A0A0A;
color: #FFFFFF;
font-family: 'Merriweather', serif;
line-height: 1.6;
}

/* Container */
.container {
max-width: 900px;
margin: 0 auto;
padding: 2rem 1rem;
}

/* Header */
header {
text-align: center;
margin-bottom: 3rem;
position: relative;
}

/* Author Name */
.author-name {
font-family: 'Great Vibes', cursive;
font-size: 3.5rem;
color: #D4AF37;
margin-bottom: 0.2rem;
position: relative;
display: inline-block;
padding: 0 1rem;
}

/* Soft Ink Splash Behind Name */
.ink-splash {
position: absolute;
top: 25px;
left: 50%;
transform: translateX(-50%);
width: 300px;
opacity: 0.15;
z-index: 0;
pointer-events: none;
}

/* Tagline */
.tagline {
font-family: 'Montserrat', sans-serif;
font-weight: 700;
font-size: 1.25rem;
color: #FF4FA8; /* pink accent */
letter-spacing: 0.05em;
margin-top: 0;
z-index: 1;
position: relative;
}

/* Featured Memoir Section */
.featured-book {
background: #111111;
border-left: 6px solid #D4AF37;
padding: 1.5rem;
margin-bottom: 3rem;
box-shadow: 0 0 15px rgba(212, 175, 55, 0.3);
}

.featured-book h2 {
color: #E9C874; /* soft gold */
font-family: 'Montserrat', sans-serif;
margin-top: 0;
}

.featured-book p {
font-size: 1.1rem;
color: #ddd;
}

/* Buttons */
.btn {
display: inline-block;
background-color: #FF4FA8;
color: white;
padding: 0.75rem 1.5rem;
font-weight: 700;
font-family: 'Montserrat', sans-serif;
border-radius: 30px;
text-decoration: none;
margin-top: 1rem;
transition: background-color 0.3s ease;
}

.btn:hover {
background-color: #D43E85;
}

/* Footer */
footer {
text-align: center;
padding: 1rem 0;
font-size: 0.9rem;
color: #666;
margin-top: 4rem;
}
</style>
</head>
<body>
<header>
<h1 class="author-name">Tina Unique</h1>
<img class="ink-splash" src="https://i.imgur.com/E1Hl8vS.png" alt="Soft Ink Splash" />
<p class="tagline">Bold. Beautiful. Powerful. Elegant.</p>
</header>

<main class="container">
<section class="featured-book">
<h2>My Memoirs</h2>
<p><strong>Becoming a Mother at 17:</strong> My journey of strength, resilience, and love, making it to 42 unscathed despite all the hardships.</p>
<p><strong>Legendary:</strong> Triumphing over trials and tribulations to stay on top and ahead of the game — proving I’m never behind.</p>
<a href="#books" class="btn">Discover My Books</a>
</section>
</main>

<footer>
&copy; 2025 Tina Unique. All rights reserved.
</footer>
</body>
</html>
