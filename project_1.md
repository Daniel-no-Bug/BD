# Проект 1

About: https://github.com/RyabovNick/databasecourse_p1/tree/master/Project1

## Сервис по заказу такси

Возможности:

1. Пользователь. Отправить заказ
2. Пользователь. Поставить оценку и комментарий
3. Водитель. Поиск заказа
4. Водитель. Выбор заказа, доступно только для водителей с оценкой более 4.8 (заказы, до которых ехать не б. е 5 минут или ближайший)
5. Водитель. Указать, что прибыл на место
6. Водитель. Указать, что начал поезду
7. Водитель. Указать, что поездка закончилась
8. Общее. Произвести расчёт стоимости заказа
9. Администратор. Просмотр статистика по каждому клиенту, сколько проходит время от приезда водителя на место до отправления.
10. Пользователь. Просмотр собственной истории заказов с пагинацией и поиском по диапазону дат
11. Водитель. Просмотр собственной истории выполненных заказов с пагинацией и поиском по диапазону дат

Доп. Задание (5 семестр): использовать любое доступное API для автозаполнения адресов (например, https://developers.google.com/maps/documentation/javascript/places-autocomplete#address_forms) или любое другое (https://tech.yandex.com/maps/geocoder/), как насчёт хранения не адреса, а координат? В PostgreSQL для работы с координатами есть postgis.
