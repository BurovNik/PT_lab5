# PT_lab4_Test

Данный проект является учебным, вариант выполнения задания 4. Лабораторная рассчитана на такие понятия как Рекурсивная функция (часть 1) и Замыкания (часть 2)

Условия заданий выглядели следующим образом: 

Часть 1

Задание 6:
Напишите рекурсивную функцию вычисления числа Фибоначчи
fibonacci, на вход которой подается целочисленное значение n.

Задание 12:
Пользователь с клавиатуры вводит целое число N. Напишите
рекурсивную функцию check_pow2, принимающую на вход 2 аргумента
(первый аргумент n, второй аргумент check_value=1) и проверяющую то,
является ли введенное значение точной степенью двойки. Если да –
выведите в терминал «YES», иначе – «NO» (без кавычек).

Задание 13:
Напишите рекурсивную функцию negative_sum, которой на вход
подается список из целочисленных значений и возвращающую сумму
отрицательных элементов списка.

Задание 14:
Напишите рекурсивную функцию recursion_pow, на вход которой
подается два целочисленных значения (х – значение, возводимое в
степень и у – степень). Функция должна возвращать x^y

Часть 2

Задание 5:
На вход функции closure_comparison поступает один из символов «>»,
«<», «=». Используя механизм замыканий, сравните два значения,
подаваемые на вход возвращаемой функции. В результате должно
возвращаться True, если результат сравнения ИСТИНА, иначе – False. В
том случае, когда на вход closure_ comparison подается неизвестный
символ – результат всегда False.

Задание 6:
На вход функции closure_del_str подается строка. Используя механизм
замыканий, удалите из строки задаваемый в возвращаемой функции
символ и верните полученный результат.

Задание 9:
Напишите функцию closure_list_pow, на вход которой подается список
целочисленных или вещественных значений. Используя механизм
замыкания верните функцию, принимающую значение степени, в
которую необходимо возвести каждый элемент списка и возвращающую
полученный результат.

----------------------------------------------------------------------
Тестирование:

Помимо выполнения заданий необходимо было провести тестирование корректности выполнения функций. Для выполнения тестирование использовался pytest
