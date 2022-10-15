**Задание 7 семинара:**

 Создать телефонный справочник с возможностью импорта и экспорта данных в нескольких форматах (txt, csv, по желанию - json, xml)

    • под форматами понимаем структуру файлов, например:в файле на одной строке хранится одна часть записи, пустая строка - разделитель
Фамилия_1

Имя_1

Телефон_1

Описание_1

Фамилия_2

Имя_2

Телефон_2

Описание_2

и т.д.в файле на одной строке хранится все записи, символ разделитель - ;
Фамилия_1,Имя_1,Телефон_1,Описание_1

Фамилия_2,Имя_2,Телефон_2,Описание_2

и т.д.

Полезный источник о работе с файлами CSV: https://all-python.ru/osnovy/csv.html

# Руководство по использованию

1. Запуск программы осуществляется файлом main.py.
2. В диалоге необходимо выбрать действие по экспорту или импорту данных.
3. Импортируемые и экспортируемые файлы находятся в той же папке. Формат ввода файлов: file.txt или file.csv