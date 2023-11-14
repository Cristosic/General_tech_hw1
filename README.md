# General_tech_hw1

1. Приведите десять типовых бизнес-процессов для предметной области ВИДЕО-ХОСТИНГ (Youtube), а также их соответствие по CRUD.

1. Смотреть видео - Read
2. Загрузить видео - Update
3. Удалить видео - Delete
4. Оставить комментарий - Create
5. Поставить лайк/дизлайк - Update
6. Регистрация - Create 
7. Подписатся на канал - Update
8. Поиск видео - Read
9. Поделится видео - Update
10. Управление профилем - Update

-Вывести название и стоимость товаров от 20 EUR.

SELECT ProductName,
       Price
FROM Products
WHERE Price >= 20;

-Вывести страны поставщиков.

SELECT Country
FROM Suppliers;

-Вывести контактные имена клиентов, кроме тех, что из France и USA.
SELECT ContactName
FROM Customers
WHERE Country <> 'France' and Country <> 'USA';
