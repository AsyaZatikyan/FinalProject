# Итоговая проверочная работа.
## Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Решение:
### Для решения задачи были созданы функции:
+ __FillArray__ для заполнения массива
+ __PrintArray__ для печати массива
+ __CountStringSymbols__ для подсчета количества элементов в массиве, длина которых меньше либо равна 3 символа
+ __GenerateNewArray__ для создания нового массива, состоящего из строк, длина которых меньше либо равна 3 символа

### Алгоритм решения:
+ создаем массив;
+ наполняем массив строками (ввод в консоли);
+ производим подсчета количества элементов в массиве, длина которых меньше либо равна 3 символа;
+ создаем новый массив размером, равным количеству подсчитанных элементов;
+ заполняем новый массив элементами, длина которых меньше либо равна 3 символа;
+ выводим на печать исходный массив и и новый массив.