<h1 align="center">Telegram Bot Web Client</h1>

<p align="center">
  🌐 Веб-приложение для управления Telegram-ботом с минималистичным и стильным интерфейсом в духе темной темы Telegram.
</p>

---

<h2>🚀 Основные функции</h2>

<ul>
  <li><strong>📨 Управление сообщениями</strong>:
    <ul>
      <li>Просмотр входящих сообщений.</li>
      <li>Отправка сообщений из веб-интерфейса.</li>
      <li>История всех сообщений с сохранением в базу данных.</li>
    </ul>
  </li>
  <li><strong>💬 Удобный интерфейс</strong>:
    <ul>
      <li>Список чатов с превью последнего сообщения.</li>
      <li>Возможность обновления списка чатов.</li>
      <li>Темная тема в стиле Telegram.</li>
    </ul>
  </li>
  <li><strong>🔐 Безопасность</strong>:
    <ul>
      <li>Вход по токену бота.</li>
      <li>Автоматическое завершение сессии при выходе.</li>
    </ul>
  </li>
  <li><strong>📊 База данных</strong>:
    <ul>
      <li>Сохранение всех сообщений и чатов.</li>
      <li>Отслеживание непрочитанных сообщений.</li>
    </ul>
  </li>
</ul>

---

<h2>🛠 Технологии</h2>

<ul>
  <li><strong>Backend</strong>:
    <ul>
      <li>Python 3.10+</li>
      <li>Flask (веб-фреймворк)</li>
      <li>SQLAlchemy (работа с базой данных)</li>
      <li>Aiogram (Telegram Bot API)</li>
    </ul>
  </li>
  <li><strong>Frontend</strong>:
    <ul>
      <li>HTML5, CSS3 (стили в духе Telegram)</li>
      <li>Минималистичный и адаптивный дизайн</li>
    </ul>
  </li>
  <li><strong>База данных</strong>:
    <ul>
      <li>SQLite (легкая и простая в использовании)</li>
    </ul>
  </li>
</ul>

---

<h2>⚙️ Установка</h2>

<ol>
  <li>Клонируйте репозиторий:
    <pre><code>git clone https://github.com/IllDieAnyway/telegram-bot-client.git
cd telegram-bot-client</code></pre>
  </li>
  <li>Установите зависимости:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Запустите приложение:
    <pre><code>python app.py</code></pre>
  </li>
  <li>Откройте в браузере:
    <pre><code>http://localhost:5000/login</code></pre>
  </li>
</ol>

---

<h2>🖥 Использование</h2>

<ol>
  <li><strong>Вход</strong>:
    ![image](https://github.com/user-attachments/assets/901cd0ba-aa3d-4075-90a1-5ad1f8b36f89)
    <ul>
      <li>Перейдите на страницу входа.</li>
      <li>Введите токен вашего Telegram-бота.</li>
    </ul>
  </li>
  <li><strong>Список чатов</strong>:
    <ul>
      <li>После входа вы увидите список всех чатов.</li>
      <li>Нажмите на чат, чтобы открыть переписку.</li>
    </ul>
  </li>
  <li><strong>Переписка</strong>:
    <ul>
      <li>Просматривайте историю сообщений.</li>
      <li>Отправляйте новые сообщения через форму ввода.</li>
    </ul>
  </li>
  <li><strong>Обновление</strong>:
    <ul>
      <li>Используйте кнопку "Обновить" для получения новых сообщений.</li>
    </ul>
  </li>
  <li><strong>Выход</strong>:
    <ul>
      <li>Нажмите "Выйти", чтобы завершить сессию.</li>
    </ul>
  </li>
</ol>

---

<h2>📁 Структура проекта</h2>

<pre>
telegram-bot-client/
├── app.py                # Основное приложение
├── bot.py                # Логика Telegram-бота
├── models.py             # Модели базы данных
├── requirements.txt      # Зависимости
├── static/               # Статические файлы (CSS, изображения)
│   └── css/
│       └── style.css
└── templates/            # HTML шаблоны
    ├── login.html
    ├── chats.html
    └── chat.html
</pre>

---

<h2>📄 Лицензия</h2>

<p>Этот проект распространяется под лицензией MIT. Подробности см. в файле <a href="LICENSE">LICENSE</a>.</p>

---

<h2>🤝 Как помочь проекту</h2>

<ol>
  <li>Сообщайте об ошибках в <a href="https://github.com/IllDieAnyway/telegram-bot-client/issues">Issues</a>.</li>
  <li>Предлагайте улучшения через Pull Requests.</li>
  <li>Делитесь проектом с друзьями и коллегами!</li>
</ol>

---

<h2>📧 Контакты</h2>

<p>Если у вас есть вопросы или предложения, пишите:</p>
<ul>
  <li><strong>Telegram</strong>: @vovaputins</li>
</ul>

---

<p align="center">Наслаждайтесь использованием! 🚀</p>
