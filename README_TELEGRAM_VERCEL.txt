Инструкция для Vercel

1. Загрузите файлы проекта на GitHub.
2. В Vercel добавьте Environment Variables:
   TELEGRAM_BOT_TOKEN = токен вашего бота
   TELEGRAM_CHAT_ID = ID вашей группы
3. В проекте НЕ нужен файл vercel.json.
4. Vercel автоматически найдёт функцию api/send-telegram.js.
5. После изменения файлов нажмите Redeploy.
