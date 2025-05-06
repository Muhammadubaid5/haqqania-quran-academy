# Haqqania Quran Academy

**Haqqania Quran Academy** is an online platform dedicated to teaching the Holy Quran to students of all ages. We provide easy, effective, and authentic Quran education through online classes.
## 🌟 Features

- Online Quran classes via Zoom or Skype
- Nazra (basic Quran reading) and Hifz (memorization) courses
- Quran teaching with proper Tajweed (pronunciation) rules
- Male and female teachers available
- Weekly progress reports for parents
- Personalized one-on-one sessions (on request)
<header>
    <nav>
        <!-- موبائل نیویگیشن کے لیے بٹن -->
        <button id="nav-toggle">☰</button> 

        <!-- نیویگیشن مینو -->
        <ul id="nav-menu">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>
/Haqqania-Quran-Academy
  ├── index.html        # مین ویب پیج
  ├── style.css         # اسٹائل شیٹ
  ├── script.js         # جاوا اسکرپٹ فائل
  ├── /assets           # میڈیا فائلز
  │    ├── /images      # تصویریں
  │    ├── /fonts       # فونٹس
  ├── /js               # جاوا اسکرپٹ فائلز
  ├── /css              # اسٹائل شیٹس
<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Haqqania Quran Academy</title>
    
    <!-- Link to CSS -->
    <link rel="stylesheet" href="css/style.css">
    
    <!-- Link to JavaScript -->
    <script src="js/script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <!-- Navigation links will go here -->
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Welcome to Haqqania Quran Academy</h1>
            <p>Learn the Quran with dedication and understanding</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Haqqania Quran Academy. All rights reserved.</p>
    </footer>
</body>
</html>
/* General reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #0044cc;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
    text-align: center;
}

#home {
    margin-top: 50px;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Haqqania Quran Academy</title>
    
    <!-- Link to CSS -->
    <link rel="stylesheet" href="css/style.css">
    
    <!-- Link to JavaScript -->
    <script src="js/script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <!-- موبائل نیویگیشن کے لیے بٹن -->
            <button id="nav-toggle">☰</button>

            <!-- نیویگیشن مینو -->
            <ul id="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Welcome to Haqqania Quran Academy</h1>
            <p>Learn the Quran with dedication and understanding.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Haqqania Quran Academy. All rights reserved.</p>
    </footer>
</body>
</html>
/* General reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #0044cc;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
    text-align: center;
}

#home {
    margin-top: 50px;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Mobile navigation menu */
#nav-menu {
    display: none; /* مینو پہلے چھپایا گیا ہے */
}

#nav-menu.active {
    display: block; /* جب 'active' کلاس ہو، تو مینو ظاہر ہو جائے گا */
}
// موبائل نیویگیشن بٹن کے لیے جاوا اسکرپٹ
const navToggle = document.querySelector('#nav-toggle');
const navMenu = document.querySelector('#nav-menu');

// بٹن پر کلک ہونے پر مینو کو دکھانا یا چھپانا
navToggle.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});
