Просто самописный бот-помошник.
Имя бота в телеграм: https://t.me/RightTimeWeatherBot
Функционал бота предельно прост: пользователь задает город и время. В последующем каждый день в назначенное время бот будет присылать пользователю сообщение с актуально погодой и прогнозом погоды на ближайший период. В любой момент времени можно изменить город или время. 
Работа бота реализована с помощью модуля pyTelegramBotAPI. Также имеется поддержка двух типов баз данных - MySQL и PostgreSQL.
Он умеет понимать в каком часовом поясе находится пользователь и принимает местное время.
Внедрен модуль apscheduler, выполняющия ряд задач в фоновом режиме.
Хостинг осуществлен с помощью сервиса pythonanywhere.com. 
