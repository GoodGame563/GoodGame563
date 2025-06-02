    <style>
        body {
            background-color: #1a1a1a;
            color: #ff0000;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            border: 2px solid #ff0000;
            padding: 20px;
            background-color: #000;
            box-shadow: 0 0 15px #ff0000;
        }
        h1, h2 {
            text-align: center;
            text-transform: uppercase;
            text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000;
        }
        h1 {
            font-size: 2.5em;
        }
        h2 {
            font-size: 1.5em;
            border-bottom: 1px solid #ff0000;
            padding-bottom: 5px;
        }
        .logo {
            display: block;
            margin: 0 auto;
            width: 150px;
        }
        .section {
            margin: 20px 0;
        }
        .tech-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            list-style: none;
            padding: 0;
        }
        .tech-list li {
            display: flex;
            align-items: center;
            gap: 5px;
        }
        .tech-list img {
            width: 20px;
            height: 20px;
        }
        .project-list {
            list-style: none;
            padding: 0;
        }
        .project-list li {
            margin: 10px 0;
        }
        .project-list a {
            color: #ff0000;
            text-decoration: none;
            text-shadow: 0 0 5px #ff0000;
        }
        .project-list a:hover {
            text-shadow: 0 0 10px #ff0000;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ff0000;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #ff0000;
            color: #000;
        }
        .note {
            font-size: 0.9em;
            text-align: center;
            margin-top: 20px;
            text-shadow: 0 0 5px #ff0000;
        }
    </style>

<body>
    <div class="container">
        <h1>Rodion</h1>
        <img src="https://example.com/arasaka-glitch-logo.png" alt="Arasaka Logo" class="logo">

        <div class="section">
            <h2>Обо мне</h2>
            <ul>
                <li><strong>Роль</strong>: Программист</li>
                <li><strong>Локация</strong>: Найт Сити</li>
            </ul>
        </div>

        <div class="section">
            <h2>Технологии</h2>
            <ul class="tech-list">
                <li><img src="https://simpleicons.org/icons/rust.svg" alt="Rust"> Rust</li>
                <li><img src="https://simpleicons.org/icons/python.svg" alt="Python"> Python</li>
                <li><img src="https://simpleicons.org/icons/csharp.svg" alt="C#"> C#</li>
                <li><img src="https://simpleicons.org/icons/go.svg" alt="Go"> Go</li>
                <li><img src="https://simpleicons.org/icons/javascript.svg" alt="JavaScript"> JavaScript</li>
                <li><img src="https://simpleicons.org/icons/postgresql.svg" alt="PostgreSQL"> PostgreSQL</li>
                <li><img src="https://simpleicons.org/icons/mongodb.svg" alt="MongoDB"> MongoDB</li>
                <li><img src="https://simpleicons.org/icons/rabbitmq.svg" alt="RabbitMQ"> RabbitMQ</li>
                <li><img src="https://nats.io/img/nats-icon-color.svg" alt="NATS"> NATS</li>
                <li><img src="https://simpleicons.org/icons/git.svg" alt="Git"> Git</li>
                <li><img src="https://simpleicons.org/icons/docker.svg" alt="Docker"> Docker</li>
                <li><img src="https://simpleicons.org/icons/linux.svg" alt="Linux"> Linux</li>
                <li><img src="https://simpleicons.org/icons/terminal.svg" alt="Bash"> Bash</li>
                <li><img src="https://simpleicons.org/icons/kubernetes.svg" alt="Kubernetes"> Kubernetes</li>
                <li><img src="https://simpleicons.org/icons/terraform.svg" alt="Terraform"> Terraform</li>
            </ul>
        </div>

        <div class="section">
            <h2>Проекты</h2>
            <ul class="project-list">
                <li><a href="https://github.com/GoodGame563/rust_project">rust_project</a>: Командная утилита на Rust для управления задачами.</li>
                <li><a href="https://github.com/GoodGame563/python_webapp">python_webapp</a>: Веб-приложение на Python с использованием Flask.</li>
                <li><a href="https://github.com/GoodGame563/go_microservice">go_microservice</a>: Микросервис на Go для обработки запросов.</li>
                <li><a href="https://github.com/GoodGame563/js_react_app">js_react_app</a>: Фронтенд-приложение на React.js.</li>
            </ul>
            <p>(Замените описания на свои, если доступны другие проекты.)</p>
        </div>

        <div class="section">
            <h2>Контакты</h2>
            <ul>
                <li><strong>GitHub</strong>: <a href="https://github.com/GoodGame563">GoodGame563</a></li>
                <li><strong>Email</strong>: (укажите, если есть)</li>
                <li><strong>Другие Платформы</strong>: (укажите, если есть)</li>
            </ul>
        </div>

        <div class="section">
            <h2>Статус Системы</h2>
            <table>
                <tr>
                    <th>Параметр</th>
                    <th>Статус</th>
                </tr>
                <tr>
                    <td>Состояние Сервиса</td>
                    <td>АКТИВЕН</td>
                </tr>
                <tr>
                    <td>Система</td>
                    <td>ЗАЩИЩЕНА</td>
                </tr>
                <tr>
                    <td>Целостность Данных</td>
                    <td>ОТЛИЧНАЯ</td>
                </tr>
                <tr>
                    <td>Безопасность</td>
                    <td>Все системы в норме</td>
                </tr>
                <tr>
                    <td>Общий Статус Системы</td>
                    <td>СТАБИЛЬНЫЙ</td>
                </tr>
            </table>
        </div>

        <div class="note">
            Этот профиль является частью базы данных アラサカ (Arasaka). Все данные подлежат строгому контролю и защите.
        </div>
    </div>
</body>

