EasyTables: учебный проект для парсинга и обработки html-таблиц
 =================
 Проект содержит следующие библиотеки:
 * libs/TableLoader.py   Содержит класс BaseTL для загрузки html-таблицы в массив данных
 * libs/Sqlite3_ORM.py   Содержит класс BaseORM для загрузки массива данных в sqlite3.db и работы с этими данными через ORM методы класса
 * libs/TableConstructor.py Содержит метод для создания html-таблицы из массива данных 
 
 Что и зачем?
 ----------------
 В файле EasyTables.py приведен пример совместной работы всех трех библиотек, а именно:
 получени данных из html-таблиц, запись данных в базу данных, выполнение sql-запросов к данным, формирование результата
 и вывод результата в html-файл
 
 Requirements:
 -----------------
 * python3.5
 * urllib3
 * beautifulsoup4
 * lxml
