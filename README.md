# 27.02.25-control-work
Контрольная работа ИЭ-72  за 27.02.24

Как работает обновленный код:
Программа считывает Excel-файл в DataFrame с помощью pd.read_excel.

Пользователь вводит номер строки, которую он хочет увидеть.

Программа проверяет, существует ли строка с таким номером в DataFrame.

Если строка существует, она выводится на экран. Если нет, выводится сообщение об ошибке.

Пример работы программы:
Если файл Книга1.xlsx содержит следующие данные:

A	  B  	C
10	20	30
40	50	60
70	80	90

И пользователь вводит 1, программа выведет:

A    40
B    50
C    60


Если пользователь введет 5, программа выведет:

Ошибка: такой строки не существует.
