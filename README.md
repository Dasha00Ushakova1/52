
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>День программиста</title>
    <link rel="stylesheet" href="styles.css"> <!-- Подключение CSS для стилей -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #23262D; /* Цвет фона */
            color: #FFFFFF; /* Цвет текста */
        }
        header {
            background-color: #4C7124; /* Цвет заголовка */
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav a {
            color: #90AACF; /* Цвет ссылок */
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline; /* Подчеркивание при наведении */
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
        }
        footer {
            background-color: #445B7D; /* Цвет подвала */
            padding: 10px;
            text-align: center;
        }
        #qr-code {
            width: 150px; /* Размер QR-кода */
            height: auto; /* Автоматическая высота */
        }
    </style>
</head>
<body>
    <header>
        <h1>День программиста</h1>
        <p>Дата: 13 сентября | Время: 10:00 - 16:00</p>
        <img src="qr-code.png" alt="QR-код на сайт мероприятия" id="qr-code"> <!-- QR-код -->
    </header>
    <nav>
        <ul>
           <li><a href="1.html">О мероприятии</a></li>
            <li><a href="README.md">Роли и задачи</a></li>
            <li><a href="3.html">Программа дня</a></li>
            <li><a href="4.html">Место проведения</a></li>
            <li><a href="5.html">Контакты</a></li>
        </ul>
    </nav>
    <main>
        <section id="roles">
            <h2>Роли и распределение задач</h2>
            <h3>Команды:</h3>
            <ul>
                <li><strong>Техники (4 человека):</strong>
                    <ul>
                        <li>Подготовка оборудования.</li>
                        <li>Настройка трансляции.</li>
                        <li>Обеспечение технической поддержки во время мероприятия.</li>
                    </ul>
                </li>
                <li><strong>Дизайнеры (2 человека):</strong>
                    <ul>
                        <li>Разработка визуального оформления.</li>
                        <li>Создание макетов баннеров, бейджей и указателей.</li>
                    </ul>
                </li>
                <li><strong>Креативщики (4 человека):</strong>
                    <ul>
                        <li>Подготовка видеороликов и презентаций.</li>
                        <li>Создание интерактивных элементов для участников.</li>
                    </ul>
                </li>
                <li><strong>Организаторы (4 человека):</strong>
                    <ul>
                        <li>Координация всех команд.</li>
                        <li>Обеспечение логистики и порядка на мероприятии.</li>
                    </ul>
                </li>
                <li><strong>Специалисты по контенту (2 человека):</strong>
                    <ul>
                        <li>Подготовка материалов для участников.</li>
                        <li>Создание информационных буклетов и программ.</li>
                    </ul>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>Следите за нами в социальных сетях!</p>
        <!-- Добавьте ссылки на социальные сети -->
    </footer>
</body>
</html>
