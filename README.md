# telegram-bot-aiogram-accept
Телеграмм бот, который имеет возможность принимать заявки людей и сохранять их в Excel таблицу.

Данный бот написан на Python, фреймворк Aiogram3, база данных SQLite3.
В боте есть админ-панель, внутри которой можно создавать и редактировать мероприятия, скачивать файл с принятыми заявками в формате Excel, просматривать отклоненные заявки.
Администратор может принимать и отклонять пользователей.
Регистрация закрывается сама, если набралось нужное количество участников.
Каждая заявка приходит администраторам в определенной форме.
