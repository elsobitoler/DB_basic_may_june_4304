## Данные для работы на семинаре: [https://disk.yandex.ru/i/OkCrZ8oNGGYzkg](https://disk.yandex.ru/i/rAvnCG19Hff5Vg)



## Задача 1
**Чему будет равна выборка:**

1. SELECT ФИО, Тел, Комментарий FROM Общий список
2. SELECT ФИО, Тел, Комментарий FROM Общий список WHERE 
Группа = «Родня»
3. SELECT Тел FROM Общий список WHERE Группа = «Друзья» 
AND Статус = «холост»
4. SELECT Д/р FROM Общий список WHERE Группа = «Университет» 
OR Статус = «холост»


## Задача 2

**Что будет результатом следующих JOIN’ов:**

1. INNER JOIN Люди, Телефоны ON id = Чей телефон
2. LEFT JOIN Люди, Телефоны ON id = Чей телефон
3. RIGHT JOIN Люди, Телефоны ON id = Чей телефон
4. FULL JOIN Люди, Телефоны ON id = Чей телефон



## Задача 3 (если все успеете)


**Что будет результатом следующих JOIN’ов:**


1. SELECT * FROM Общий список
2. SELECT ФИО, Тел FROM Общий список WHERE (Комментарий= «рабочий» OR Комментарий= «личный») AND Группа = «Работа»
3. SELECT ФИО FROM Общий список WHERE (Группа = «Друзья» OR Группа = «Школа») AND Статус != «женат»
4. SELECT ФИО, Адрес, Тел FROM Общий список WHERE Адрес != «Сочи» AND Группа != «Родня» OR Группа = «Родня» AND Адрес = «Москва»
5. SELECT ФИО, Тел, Коммент FROM Люди LEFT JOIN Телефоны ON id = Чей телефон
6. SELECT * FROM Люди INNER JOIN Телефоны ON id = Чей телефон INNER JOIN Адреса ON id = Чей адрес
7. SELECT ФИО, Тел, Адрес FROM Люди INNER JOIN Телефоны ON id = Чей телефон INNER JOIN Адреса ON id = Чей адрес WHERE ФИО = «Петров П.П.»

## Дополнительно, после кто успел все! Кто сделал первые три задачи выше! Новая таблица, не связанная с таблицами выше!: https://disk.yandex.ru/i/xFkAttNoQJbd1g

## Задача 4.1 Выполните Full Join для первой вкладки и Full join - для третьей вкладки
## Задача 4.2 Выполнить Select ФИО, Адрес2, комментарий из общего списка для таблицы на второй вкладке

## Google Sheets для работы по залам:
**Зал 1(Основной зал)** : [Ссылка на документ](https://docs.google.com/spreadsheets/d/17qyyi52Sfig6IjJceZzCuwCrwQL2mEIIfZz2E7aErws/edit?usp=sharing)

**Зал 2** : [Ссылка на документ](https://docs.google.com/spreadsheets/d/1aXT6bLoKz_IXhsGQs-1SDWAJZoKa9PWH6WgSGYT94E4/edit?usp=sharing)

**Зал 3** : [Ссылка на документ](https://docs.google.com/spreadsheets/d/1Ow-nREdv2JBt5BnH92udDvrHhxuWj3NhlhBTD3PPF6I/edit?usp=sharing)

**Зал 4** : [Ссылка на документ](https://docs.google.com/spreadsheets/d/1kDlXciV32ZbUvEqFJf_HCY-4ZbQrGIJzm_JZDqV0HdI/edit?usp=sharing)
