<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>День программиста</title>
    <link rel="stylesheet" href="styles.css"> <!-- Подключение CSS для стилей -->
</head>
<body>
    <header>
        <h1>День программиста</h1>
        <p>Дата: 13 сентября | Время: 10:00 - 16:00</p>
        <p>Место проведения: Актовый зал колледжа</p>
        <img src="qr-code.png" alt="QR-код на сайт мероприятия" id="qr-code"> <!-- QR-код -->
    </header>
    <nav>
        <ul>
            <li><a href="#about">О мероприятии</a></li>
            <li><a href="#program">Программа дня</a></li>
            <li><a href="#location">Место проведения</a></li>
            <li><a href="#contact">Контакты</a></li>
        </ul>
    </nav>
    <main>
        <section id="about">
            <h2>О мероприятии</h2>
            <p>«День программиста» — это уникальная возможность для студентов и профессионалов в области программирования встретиться, обменяться опытом и узнать о последних тенденциях в индустрии.</p>
        </section>
        <section id="program">
            <h2>Программа дня</h2>
            <table>
                <tr>
                    <th>Время</th>
                    <th>Действие</th>
                    <th>Ответственный</th>
                </tr>
                <tr>
                    <td>10:00 - 10:30</td>
                    <td>Регистрация участников</td>
                    <td>Организаторы</td>
                </tr>
                <tr>
                    <td>10:30 - 11:00</td>
                    <td>Открытие мероприятия</td>
                    <td>Ведущий</td>
                </tr>
                <tr>
                    <td>11:00 - 12:00</td>
                    <td>Лекция «Будущее программирования»</td>
                    <td>Спикер</td>
                </tr>
                <tr>
                    <td>12:00 - 13:00</td>
                    <td>Мастер-класс «Основы веб-разработки»</td>
                    <td>Инструктор</td>
                </tr>
                <tr>
                    <td>13:00 - 14:00</td>
                    <td>Обед</td>
                    <td>—</td>
                </tr>
                <tr>
                    <td>14:00 - 15:00</td>
                    <td>Панельная дискуссия «Тренды в программировании»</td>
                    <td>Модератор</td>
                </tr>
                <tr>
                    <td>15:00 - 16:00</td>
                    <td>Закрытие мероприятия</td>
                    <td>Ведущий</td>
                </tr>
            </table>
        </section>
        <section id="location">
            <h2>Место проведения</h2>
            <p>Aктовый зал колледжа. Для онлайн-участников будет доступна трансляция через Zoom.</p>
        </section>
    </main>
    <footer id="contact">
        <h2>Контакты организаторов:</h2>
        <p>Email: organizer@example.com</p>
        <p>Телефон: +7 (123) 456-78-90</p>
        <p>Следите за нами в социальных сетях!</p>
        <!-- Добавьте ссылки на социальные сети -->
    </footer>
    <script>
        // Здесь можно добавить JavaScript для интерактивности
        // Например, обработка событий или анимации
        // ...
    </script>
</body>
<style>
body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    margin: 20px 0;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 15px;
}

main {
    padding: 20px;
}

table {
    width: 100%;
    border-collapse: collapse;
}

table, th, td {
    border: 1px solid black;
}

th, td {
    padding: 10px;
}

footer {
    background-color: #f1f1f1;
    padding: 10px;
}
#qr-code {
   width: 150px; /* Размер QR-кода */
   height:auto; /* Автоматическая высота */
}
/* Добавьте дополнительные стили по необходимости */
</style>
