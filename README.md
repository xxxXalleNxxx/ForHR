<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой GitHub Профиль</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
        }
        .container {
            background-color: #161b22;
            border-radius: 10px;
            padding: 30px;
            border: 1px solid #30363d;
        }
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        .welcome {
            font-size: 2.5em;
            color: #58a6ff;
            margin-bottom: 10px;
        }
        .subtitle {
            font-size: 1.2em;
            color: #8b949e;
        }
        .projects-section {
            margin-top: 40px;
        }
        .project-card {
            background-color: #21262d;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            transition: transform 0.2s, border-color 0.2s;
        }
        .project-card:hover {
            transform: translateY(-2px);
            border-color: #58a6ff;
        }
        .project-title {
            color: #58a6ff;
            font-size: 1.3em;
            margin-bottom: 10px;
        }
        .project-description {
            color: #8b949e;
            margin-bottom: 15px;
        }
        .project-link {
            color: #58a6ff;
            text-decoration: none;
            font-weight: bold;
        }
        .project-link:hover {
            text-decoration: underline;
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }
        .tech-tag {
            background-color: #238636;
            color: white;
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 0.8em;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 class="welcome">👋 Приветствую на моём GitHub!</h1>
            <p class="subtitle">Здесь я делюсь своими проектами и исследованиями в мире разработки</p>
        </div>

        <div class="projects-section">
            <h2 style="color: #58a6ff; border-bottom: 2px solid #30363d; padding-bottom: 10px;">🚀 Мои проекты</h2>
            
            <!-- Проект 1 -->
            <div class="project-card">
                <div class="project-title">🎯 Название проекта 1</div>
                <div class="project-description">
                    Краткое описание проекта. Что он делает, какие технологии использует и для чего предназначен.
                </div>
                <a href="" class="project-link">📁 Ссылка на проект →</a>
                <div class="tech-stack">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Django</span>
                    <span class="tech-tag">PostgreSQL</span>
                </div>
            </div>

            <!-- Проект 2 -->
            <div class="project-card">
                <div class="project-title">🔧 Название проекта 2</div>
                <div class="project-description">
                    Описание второго проекта. Его основные функции и особенности реализации.
                </div>
                <a href="" class="project-link">📁 Ссылка на проект →</a>
                <div class="tech-stack">
                    <span class="tech-tag">JavaScript</span>
                    <span class="tech-tag">React</span>
                    <span class="tech-tag">Node.js</span>
                </div>
            </div>

            <!-- Проект 3 -->
            <div class="project-card">
                <div class="project-title">📊 Название проекта 3</div>
                <div class="project-description">
                    Описание третьего проекта. Возможно, это анализ данных или мобильное приложение.
                </div>
                <a href="" class="project-link">📁 Ссылка на проект →</a>
                <div class="tech-stack">
                    <span class="tech-tag">Java</span>
                    <span class="tech-tag">Spring Boot</span>
                    <span class="tech-tag">MySQL</span>
                </div>
            </div>

            <!-- Проект 4 -->
            <div class="project-card">
                <div class="project-title">🤖 Название проекта 4</div>
                <div class="project-description">
                    Ещё один интересный проект с описанием его функциональности и назначения.
                </div>
                <a href="" class="project-link">📁 Ссылка на проект →</a>
                <div class="tech-stack">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Machine Learning</span>
                    <span class="tech-tag">TensorFlow</span>
                </div>
            </div>
        </div>

        <div style="margin-top: 40px; text-align: center; color: #8b949e; font-size: 0.9em;">
            <p>📧 Свяжитесь со мной: <a href="mailto:your-email@example.com" style="color: #58a6ff;">your-email@example.com</a></p>
        </div>
    </div>
</body>
</html>
