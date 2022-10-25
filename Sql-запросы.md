SHOW TABLES-показывает таблицы находящиеся в базе данных

SELECT * FROM users- запрос данных из  таблицы пользователи

SELECT * FROM users WHERE name = 'Имя' and fam = 'Фамилия'- запрсо данных по пользователю

CREATE TABLE 'chotko'- создание новой таблицы в базе данных(chotko)

INSERT INTO table_name VALUES (' ')- внести данные в определённую таблицу

SELECT * FROM users, grades WHERE users.user_id = grades.user_id- обьединение данных из таблиц оценки и пользователи, которым они были выставлены

