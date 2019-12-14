# guestbook (страница отзывов, гостевая книга на сайт)
Модуль страницы с отзывами (php с записью в БД MySQL).

Простая форма гостевой страницы с возможностью выбора пользователями типа сообщения и небольшой защитой от спама путем необходимости ввода значения суммы чисел.

Способ встраивания модуля:
1. импортировать файл gb_posts.sql в свою базу данных;
2. в файле index.php задать свои настройки подключения к БД (указать в строке $link свой хост, имя, пароль, а также созданную БД для размещения информации о постах в гостевой книге).
3. менять стили в файле main.css по своему вкусу.

![Пример отрисовки страницы](https://github.com/bagvi/guestbook/blob/master/gb.png)
