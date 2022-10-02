# sf_data_science_1
SF homework_1
From the [SkillFactory Data Scirnce cource](http://skillfactory.ru/data-scientist).

## Проект

* [Проект 0. Игра: Угадай число за меньше чем 20 попыток](https://github.com/IliaMishin/sf_data_science_1/tree/main/project_0)
#Проет 0. Угадай число (меньше, чем 20 попыток)
##
[1. Описание проекта] (https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Описание-проекта)
[2. Какой кейс решаем?](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Какой-кейс-решаем)
[3. Краткая информация о данных](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Краткая-информация-о-данных)
[4. Этапы работы над проектом](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Этапы-работы-над-проектом)
[5. Результат](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Результат)
[6. Выводы](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Выводы)

### Описание проекта
Угадать загаданное число за минимальное количество попыток.

:arrow_up:[к оглавлению](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Оглавление)

### Какой кейс решаем?
Нужно написать программу, которая угадывает число за меньше чем 20 попыток

** Условие соревнования: **
- Компьютер загадывает целое число от 1 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.
- Необходимо добиться того, чтобы программа угадывала число меньше, чем за 20 попыток.

** Метрика качества**
Результат оценивания по среднему количеству попыток при 1000 повторений

**Что практикуем**
Учимся писать хороший код на python


### Краткая информация о данных
 По умолчанию рандомно загадываемое число компьютером в диапазоне 1-100.
 
:arrow_up:[к оглавлению](https://github.com/IliaMishin/sf_data_science_1/blob/main/README.md#Оглавление)

### Этапы работы над проектом
добавление в шаблон переменной end_1, в случае, когда predict_number больше или меньше number, то вычислиятся модуль разницы между ними, что и является переменной sub_1, затем  predict_number  складывается с sub_1 и получается число end_1, которое равно number 

### Результаты:
Алгоритм угадывает число в среднем за:5 попыток

### Выводы:
По среднему количеству попыток при 1000 повторений алгоритму требуется 5 попыток, чтобы угадать число, загаданное от 0-100



