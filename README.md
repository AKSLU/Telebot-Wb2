# Telebot-Wb2


📦 Описание проекта

Это Telegram-бот, который позволяет авторизованным пользователям получать информацию о товаре на платформе Wildberries, включая:

Название товара

Анализ выгодности текущей цены (на основе средней цены)

Конвертацию цены из рублей в тенге



⚙️Функциональность
Бот поддерживает следующие команды: 

Команда	Описание

/start	Проверка доступа и отображение ID пользователя

/info	Получение названия товара по артикулу

/price	Получение цен и анализ текущей стоимости товара



🔐Авторизация

Доступ к командам ограничен. Разрешённый список пользователей хранится в файле confing.py в переменной WHITELIST.
