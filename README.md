### Название: Socially
### Идея
Общедоступная и интуитивно понятная платформа для коммуникации и общения (соцсеть). С выбором типа потребляемого контента (видео, новости и т.д.)
### Реализация:
Есть основной шаблон HTML с навигационной панелью. Существует 4
 типа контента: видео, новости, посты (анонимные и обычные) и комментарии.
 + На странице с сеткой постов отображаются их карточки и на каждую публикацию можно зайти, прочитать, лайкнуть и оставить комментарий. 
+ Из страницы с сеткой новостей можно непосредственно попасть на вкладку новости, так же прочесть её неполное содержимое и перейти к первоисточнику. Аналогично и с видео.
+	Реализован поиск каждого типа контента по ключевому слову на отдельной странице.
+	Также есть личный кабинет пользователя, его профиль, подписчики и подписки, и топ пользователей.
+	Есть телеграмм-бот для создания анонимных постов (их можно создавать без авторизации на сайте проекта)
### Начало работы:
+ Сайт: http://biturious.space:5000
+ Локальный запуск:
   1)	Нужно запустить скрипт main.py в директории проекта
    2)	После запуска скрипта откроется командная строка
    3)	Далее нужно перейти в браузер и вписать в адресную строку следующий текст: “http://127.0.0.1:5000”
    4)	Вы попадёте на главную страницу сайта проекта
    5)	Наслаждайтесь пользованием
+	Запуск телеграмм-бота (локально, если бот не работает):    
    1)	Запустите файл «tg_bot.py», он находится в директории проекта – теперь можете пользоваться ботом @AnonNoteBot в телеграмме.
### Особенности:
+	Дополнительные таблицы по работе с БД
+	Система вложенных комментариев с помощью рекурсии
+	Разделение результатов выдачи поиска на страницы
+	Система регистрации и авторизации
+	Система лайков и подписок
+	Отображение контента в виде сетки
+	Изображения хранятся в БД в виде пути к файлу
+	Собственный API сайта
+	Множественный выбор категории поста
+	Телеграм-бот



 




 


 
