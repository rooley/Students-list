# Students-list
1. БД
 - Создать базу данных в MySQL для хранения данных по успеваемости студентов;
 - Таблица предметов;
 - Таблица студентов;
 - Таблица оценок;
 - Связать между собой внешними ключами;
 - Студент посещает несколько предметов;
 - На каждый предмет ходит несколько студентов;
 - В таблице оценок хранится информация по всем оценкам студента по каждому предмету, т.е. комбинация предмет / оценка в этой таблице не уникальна;
 - Заполнить базу тестовыми данными.

2. Запрос 
 - Написать запрос, вычисляющий среднюю оценку каждого студента по каждому предмету.

3. Отчет (src/main/resources/StudentsList.jrxml)
 - Поставить iReport.
 - Создать макет отчета по успеваемости студентов в следующем виде:
       Вывести предмет;
       Под предметом вывести список всех студентов, посещающих данный предмет, со средней оценкой по данному предмету;
       Вывести среднюю оценку по предмету среди всех студентов, посещающих данный предмет;
       Перейти к следующему предмету.
 - Подсказки:
       Использовать ранее написанный запрос для вывода средних оценок студентов по предмету;
       Использовать группировку iReport для предметов;
       Использовать переменные iReport для подсчета средней оценки среди всех студентов, посещающих предмет.

4. 
 - Скачать библиотеку JasperReports;
 - Подключиться к базе через JDBC;
 - Выполнить запрос и представить результаты выполнения запроса в виде списка java-объектов;
 - Используя API JasperReports, список объектов в качестве исходных данных отчета и модифицированный шаблон отчета, созданный в п.3, получить отчет средствами Java.
