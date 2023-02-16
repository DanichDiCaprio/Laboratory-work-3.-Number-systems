# Laboratory-work-3.-Number-systems

Задача 1. Целое: значение - запись
Источник: базовая
Имя входного файла: input.txt
Имя выходного файла: output.txt
Ограничение по времени: 1 секунда
Ограничение по памяти: разумное
Перевести заданное целое число из десятичной системы счисления в 𝑏-ичную систему
счисления.
Формат входных данных
В первой строке входного файла записано целое число 𝑏 – основание системы счисления,
в которую нужно перевести число (2 6 𝑏 6 16) .
Во второй строке дана десятичная запись целого числа 𝑁 (0 6 𝑏 6 106
) .
Формат выходных данных
В выходной файл необходимо вывести представление числа 𝑁 в 𝑏-ичной системе счисления. Цифры, большие 9, выводить маленькими буквами латинского алфавита.
Пример
input.txt output.txt
2
25
11001

Задача 2. Целое: запись - значение
Источник: базовая
Имя входного файла: input.txt
Имя выходного файла: output.txt
Ограничение по времени: 1 секунда
Ограничение по памяти: разумное
Перевести заданное целое число из 𝑏-ичной в десятичную систему счисления.
Формат входных данных
В первой строке входного файла записано целое число 𝑏 – основание системы счисления, в
которой записано число, которое нужно перевести (2 ≤ 𝑏 ≤ 16) .
Во второй строке дана запись целого числа 𝑁 в 𝑏-ичной системе счисления (0 ≤ 𝑏 ≤ 106
).
Цифры, большие 9, обозначаются маленькими буквами латинского алфавита.
Формат выходных данных
В выходной файл необходимо вывести десятичную запись целого числа – значение числа
𝑁, записанного во входном файле.
Пример
input.txt output.txt
2
11001
25

Задача 3. Дробное: значение - запись
Источник: основная
Имя входного файла: input.txt
Имя выходного файла: output.txt
Ограничение по времени: 1 секунда
Ограничение по памяти: разумное
Перевести заданное дробное число из десятичной системы счисления в 𝑏-ичную систему
счисления.
Формат входных данных
В первой строке входного файла записаны два целых числа 𝑏 и 𝑘 – основание системы счисления, в которую нужно перевести число, и максимальное количество знаков после
𝑏-ичной точки (2 6 𝑏 6 16, 1 6 𝑘 6 20) .
Во второй строке дана десятичная запись дробного числа 𝑁 (0 < 𝑁 < 1) .
Формат выходных данных
В выходной файл необходимо вывести представление числа 𝑁 в 𝑏-ичной системе счисления, не более чем с 𝑘 знаками после точки. Выравнивающие нули не выводить. Цифры,
большие 9, выводить маленькими буквами латинского алфавита.
Дробную часть вычислять с точностью до 10−5
.
Примеры
input.txt output.txt
2 8
0.25
0.01
3 4
0.25
0.0202

Задача 4. Дробное: запись - значение
Источник: основная
Имя входного файла: input.txt
Имя выходного файла: output.txt
Ограничение по времени: 1 секунда
Ограничение по памяти: разумное
Перевести заданное дробное число из 𝑏-ичной системы счисления в десятичную систему
счисления.
Формат входных данных
В первой строке входного файла записано целое число 𝑏 – основание системы счисления,
из которой нужно перевести число (2 6 𝑏 6 16).
Во второй строке дана 𝑏-ичная запись дробного числа 𝑁 (0 < 𝑁 < 1). Ее длина не превосходит 50. Цифры, большие 9, обозначаются маленькими буквами латинского алфавита.
Формат выходных данных
В выходной файл необходимо вывести десятичное представление вещественного числа 𝑁
с пятью знаками после точки.
Примеры
input.txt output.txt
2
0.01
0.25000
3
0.0202
0.24691

Задача 5. Перевод целых чисел
Источник: повышенной сложности
Имя входного файла: input.txt
Имя выходного файла: output.txt
Ограничение по времени: 1 секунда
Ограничение по памяти: разумное
Дано число 𝑁 в 𝑝-ичной системе счисления.
Требуется выполнить перевод числа 𝑁 в 𝑞-ичную систему счисления.
Формат входных данных
В первой строке через пробел записаны три числа 𝑝, 𝑞 и 𝑁 (2 6 𝑝, 𝑞 6 36). Гарантируется,
что значение числа 𝑁 в десятичной системе счисления не превосходит 109
.
Для записи цифр, значения которых в десятичной системе счисления имеют значения от
10 до 36, используются строчные латинские буквы ‘a‘, ‘b‘, . . ., ‘z‘.
Формат выходных данных
Выведите число 𝑁 в 𝑞-ичной системе счисления.
Примеры
input.txt output.txt
2 16 101010 2a
7 20 22 g
20 7 g 22

Задача 6. Перевод вещественных чисел
Источник: повышенной сложности
Имя входного файла: input.txt
Имя выходного файла: output.txt
Ограничение по времени: 1 секунда
Ограничение по памяти: разумное
Перевести заданное вещественное число из 𝑏1-ичной системы счисления в 𝑏2-ичную систему счисления.
Формат входных данных
В первой строке входного файла записаны три целых числа 𝑏1, 𝑏2 и 𝑘, где:
𝑏1 – основание системы счисления, в которой записано входное число 𝐴,
𝑏2 – основание системы счисления, в которую нужно перевести число 𝐴,
𝑘 – максимальное количество знаков после 𝑏2-ичной точки (2 6 𝑏1, 𝑏2 6 16, 1 6 𝑘 6 20).
Во второй строке дана запись числа 𝐴 в системе счисления с основанием 𝑏1. Число может
быть и целым и вещественным. Целая часть отделяется от дробной точкой. Длина записи
числа не превосходит 100. Цифры, большие 9, обозначаются маленькими буквами латинского
алфавита.
Формат выходных данных
В выходной файл необходимо вывести запись числа в системе счисления с основанием
𝑏2. Дробную часть, если таковая имеется, выводить не более чем с 𝑘 знаками после точки.
Несущественные нули не выводить. Вычисления производить с точностью до 10−5
. Цифры,
большие 9, выводить маленькими буквами латинского алфавита.
Если входное число задано некорректно, то вывести слово NO.
Примеры
input.txt output.txt
2 4 10
11101.01101
131.122
2 3 10
11101.01201
NO
3 9 2
2102
72


