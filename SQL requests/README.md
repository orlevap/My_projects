# Проект - Написание запросов на SQL

### Библиотеки
pandas, SQLAlchemy

## Задача
Проанализировать базу данных крупного сервиса для чтения книг по подписке.
Подключиться к базе данных через Python, написать запросы на SQL и вывести их результаты.

## Описание
Данные находились в 5 разных таблицах, о книгах, авторах, издательствах, рейтингах и рецензиях. Необходимо было сделать следующие запросы:

   - Количество книг вышедших после 1 января 2000 года
   - Количество обзоров и средняя оценка для каждой книги
   - Издательство, которое выпустило наибольшее число книг толще 50 страниц
   - Автор с самой высокой средней оценкой книг. Книги с 50 и более оценками
   - Среднее количество обзоров от пользователей, которые поставили больше 50 оценок

Использованы JOIN, подзапросы и фильтрация результатов.