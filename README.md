<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мое Портфолио</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 20px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.2em;
            opacity: 0.9;
        }
        
        nav {
            background: #333;
            padding: 15px;
            position: sticky;
            top: 0;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
        }
        
        nav a:hover {
            color: #667eea;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        section {
            margin: 40px 0;
        }
        
        section h2 {
            color: #667eea;
            margin-bottom: 20px;
            font-size: 2em;
        }
        
        .project {
            background: #f4f4f4;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }
        
        .project h3 {
            color: #333;
            margin-bottom: 10px;
        }
        
        .project p {
            margin: 10px 0;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background: #667eea;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        footer a {
            color: #667eea;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Иван Иванов</h1>
        <p>Full-Stack Developer | UI/UX Designer</p>
    </header>
    
    <nav>
        <a href="#about">Обо мне</a>
        <a href="#projects">Проекты</a>
        <a href="#skills">Навыки</a>
        <a href="#contact">Контакты</a>
    </nav>
    
    <div class="container">
        <!-- О МНЕ -->
        <section id="about">
            <h2>Обо мне</h2>
            <p>
                Привет! Я разработчик с опытом создания веб-приложений. 
                Люблю создавать красивые и функциональные сайты.
            </p>
        </section>
        
        <!-- ПРОЕКТЫ -->
        <section id="projects">
            <h2>Мои Проекты</h2>
            
            <div class="project">
                <h3>🎯 Проект 1: E-commerce сайт</h3>
                <p>Интернет-магазин на React с корзиной и оформлением заказа</p>
                <p><strong>Технологии:</strong> React, Node.js, MongoDB</p>
                <p><a href="#" style="color: #667eea;">Посмотреть проект →</a></p>
            </div>
            
            <div class="project">
                <h3>🎨 Проект 2: Дизайн сайта</h3>
                <p>Современный лендинг для IT компании</p>
                <p><strong>Технологии:</strong> HTML, CSS, JavaScript</p>
                <p><a href="#" style="color: #667eea;">Посмотреть проект →</a></p># yourusername.github.io
