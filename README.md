# 📢 Чат Приложение с Node.js

## 🧾 Описание

Това е уеб базирано чат приложение, проектирано с помощта на Node.js, Express и WebSocket (чрез Socket.IO), което позволява комуникация в реално време между потребители.

Приложението поддържа:
- Регистрация и вход
- Управление на сесии
- Асинхронен обмен на съобщения чрез WebSocket
- Съхранение на съобщенията и потребителите в SQLite база данни
- Зареждане на последните съобщения при влизане
- Pug шаблони за визуализиране на потребителския интерфейс

## 🚀 Онлайн Достъп

📎 Достъпно и онлайн: [https://chat-app-1te1.onrender.com](https://chat-app-1te1.onrender.com)

## 🛠️ Използвани технологии

- Node.js
- Express
- Socket.IO
- SQLite3
- Pug (шаблонен енджин)
- express-session

## ▶️ Стартиране локално

```bash
git clone https://github.com/AlexanderGyulev/chat-app.git
cd chat-app
npm install
node ./bin/www

