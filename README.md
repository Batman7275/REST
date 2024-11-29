# REST<!DOCTYPE html>
<html lang="bg">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моят Pinterest сайт</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Добре дошли в почивката </h1>
        <nav>
            <a href="#signup">Регистрация</a>
            <a href="#login">Вход</a>
        </nav>
    </header>

    <section id="signup">
        <h2>Регистрация</h2>
        <form id="signup-form">
            <input type="text" id="username" placeholder="Потребителско име" required><br>
            <input type="email" id="email" placeholder="Имейл" required><br>
            <input type="password" id="password" placeholder="Парола" required><br>
            <button type="submit">Регистрирай се</button>
        </form>
    </section>

    <section id="login">
        <h2>Вход</h2>
        <form id="login-form">
            <input type="email" id="login-email" placeholder="Имейл" required><br>
            <input type="password" id="login-password" placeholder="Парола" required><br>
            <button type="submit">Влез</button>
        </form>
    </section>

    <section id="gallery">
        <h2>Твоите изображения</h2>
        <!-- Тук ще се показват изображенията, които потребителите качват -->
        <div id="image-gallery"></div>
    </section>

    <footer>
        <p>&copy; 2024 Моето Pinterest. Всички права запазени.</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
