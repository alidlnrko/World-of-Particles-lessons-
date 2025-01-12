<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;500;600;700&family=Rubik+Glitch&display=swap');

        body {
            font-family: "Cormorant Garamond", serif;
            font-weight: 300;
            background-color: #333;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        header {
            width: 100%;
            background-color: #333;
            padding: 10px 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            position: fixed;
            top: 0;
            z-index: 1000;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .navbar {
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 1200px;
            margin: auto;
        }

        .nav-links {
            display: flex;
            list-style: none;
        }

        .nav-links li {
            margin-left: 20px;
        }

        .nav-links a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #aa00ff;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        .container video {
            width: 100%;
            max-width: 800px;
            border: 4px solid blueviolet;
            border-radius: 50px;
            box-shadow: 0 0 25px 0 #aa00ff;
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
        }

        label {
            font-size: 1.2em;
            line-height: 1.5;
        }

        input[type="radio"] {
            margin-right: 10px;
            transform: scale(1.2);
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
            transition: background-color 0.3s;
        }

        button:hover {
            transition: 1s all ease;
            box-shadow: #4CAF50 0 0 25px 0;
            background-color: #00ff0d;
        }

        #result {
            margin-top: 20px;
            font-size: 1.5em;
            text-align: center;
        }

        /* Мобильная адаптация */
        @media (max-width: 768px) {
            .nav-links {
                flex-direction: column;
                align-items: center;
                display: none;
            }

            .nav-links.active {
                display: flex;
            }

            .logo {
                font-size: 18px;
            }

            .container video {
                width: 100%;
            }

            button {
                font-size: 1em;
            }

            h1 {
                font-size: 1.5em;
            }

            label {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="navbar">
            <a href="#" class="logo">world of particles</a>
            <ul class="nav-links">
                <li><a href="https://alidlnrko.github.io/World-of-Particle/">в меню</a></li>
            </ul>
            <div class="nuclear">
                <span></span>
            </div>
        </nav>
    </header>
    <section class="gallery-of-lessons">
        <h1 class="page-title">уроки</h1>
        <div class="card-container">
            <div class="card">
                <img src="https://i0.wp.com/alittlebithuman.com/wp-content/uploads/2021/03/schrodingers-cat.jpg?resize=1024%2C576&ssl=1" alt="Placeholder">
                <div class="card-content">
                    <h2 class="card-title">квантовая физика</h2>
                    <a href="c:\Users\user\Desktop\ib project 2024-2025\web\quantym_module.html" class="card-button">читать/смотреть видеоурок</a>
                </div>
            </div>
            <video class="background-video" autoplay muted loop>
                <source src="vecteezy_in-bohr-atomic-structure-electrons-orbit-nucleus-in-fixed_47377875.mp4" type="video/mp4">
                Ваш браузер не поддерживает тег видео.
            </video>
        </div>
    </section>
</body>
</html>
