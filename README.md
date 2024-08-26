<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>پروفایل من</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        h2, h3 {
            text-align: center;
            color: #333;
        }
        p {
            text-align: center;
            color: #555;
            line-height: 1.6;
        }
        .skills, .projects {
            border: 2px solid #ccc;
            padding: 15px;
            border-radius: 10px;
            background-color: #fff;
            width: fit-content;
            margin: 20px auto;
            text-align: center;
        }
        .skills img, .projects img {
            margin: 10px;
        }
        .projects ul {
            list-style-type: none;
            padding: 0;
        }
        .projects li {
            margin: 10px 0;
        }
        .projects a {
            text-decoration: none;
            color: #0366d6;
            font-size: 18px;
        }
        .projects a:hover {
            text-decoration: underline;
        }
        hr {
            border: 1px solid #ccc;
            margin: 20px auto;
            width: 80%;
        }
        .language-buttons {
            text-align: center;
            margin: 20px 0;
        }
        .language-buttons button {
            margin: 5px;
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
        }
        .hidden { display: none; }
    </style>
</head>
<body>
    <div class="language-buttons">
        <button onclick="changeLanguage('fa')">فارسی</button>
        <button onclick="changeLanguage('en')">English</button>
    </div>
    <img align='center' src='https://raw.githubusercontent.com/imrrobat/imrrobat/d1b244e170d2b75fdda3efd499eaaf163f7a617c/images/github-contribution-grid-snake.svg' alt="GitHub Contribution Grid">
    <h2 id="title-fa">سلام👋 من برسام هستم</h2>
    <h2 id="title-en" class="hidden">Hello👋 I'm Barsam</h2>
    <p id="description-fa">متولد ۱۳۸۲، برنامه‌نویس PHP 🐘 و دانشجوی ترم چهارم مهندسی کامپیوتر 🎓. برنامه‌نویسی را از اواخر دوران دبیرستان آغاز کرده‌ام و علاقه زیادی به دنیای کامپیوتر دارم. مشتاق یادگیری زبان‌های برنامه‌نویسی جدید و ورود به دنیای شبکه‌های کامپیوتری هستم. در حال حاضر به دنبال یک شرکت مناسب برای گذراندن دوره کارآموزی‌ام می‌باشم.</p>
    <p id="description-en" class="hidden">Born in 1983, I am a PHP developer 🐘 and a fourth-semester Computer Engineering student 🎓. I started programming in the later years of high school and have a strong interest in the world of computers. I am eager to learn new programming languages and enter the field of computer networks. Currently, I am looking for a suitable company for my internship.</p>
    <h3 id="skills-title-fa" class="hidden">My Skills</h3>
    <h3 id="skills-title-en">مهارت‌های من</h3>
    <div class="skills">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" width="50" height="50"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" width="50" height="50"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" width="50" height="50"/>
        <img src="https://www.vectorlogo.zone/logos/laravel/laravel-icon.svg" alt="Laravel" width="50" height="50"/>
    </div>    
    <h3 id="projects-title-fa" class="hidden">My Projects</h3>
    <h3 id="projects-title-en">نمونه‌کارهای من</h3>
    <hr>
    <div class="projects">
        <ul>
            <li>
                <a href="https://github.com/Barsam-Divi/php-shop" target="_blank">
                    <strong id="project1-title-fa" class="hidden">Project 1: PHP Website</strong>
                    <strong id="project1-title-en">پروژه ۱: وبسایت با PHP</strong>
                </a>
                <p id="project1-desc-fa" class="hidden">Backend development of a website using PHP.</p>
                <p id="project1-desc-en">توسعه‌ بک‌اند وبسایت با استفاده از PHP.</p>
            </li>
            <li>
                <a href="https://github.com/Barsam-Divi/laravel-shop" target="_blank">
                    <strong id="project2-title-fa" class="hidden">Project 2: Laravel Website</strong>
                    <strong id="project2-title-en">پروژه ۲: وبسایت با Laravel</strong>
                </a>
                <p id="project2-desc-fa" class="hidden">Development of a website using the Laravel framework.</p>
                <p id="project2-desc-en">ساخت و توسعه وبسایت با استفاده از فریم‌ورک Laravel.</p>
            </li>
            <li>
                <a href="https://github.com/Barsam-Divi/laravel-Api" target="_blank">
                    <strong id="project3-title-fa" class="hidden">Project 3: Laravel API</strong>
                    <strong id="project3-title-en">پروژه ۳: API با Laravel</strong>
                </a>
                <p id="project3-desc-fa" class="hidden">Development of an API using the Laravel framework.</p>
                <p id="project3-desc-en">توسعه یک API با استفاده از فریم‌ورک Laravel.</p>
            </li>
        </ul>
    </div>
    <script>
        function changeLanguage(lang) {
            var elementsFa = document.querySelectorAll('[id$="-fa"]');
            var elementsEn = document.querySelectorAll('[id$="-en"]');
            if (lang === 'fa') {
                elementsFa.forEach(element => element.classList.remove('hidden'));
                elementsEn.forEach(element => element.classList.add('hidden'));
            } else if (lang === 'en') {
                elementsFa.forEach(element => element.classList.add('hidden'));
                elementsEn.forEach(element => element.classList.remove('hidden'));
            }
        }
    </script>

</body>
</html>


