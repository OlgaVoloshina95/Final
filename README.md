# Условия задачи 

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] [“1234”, “1567”, “-2”, “computer science”] → [“-2”] [“Russia”, “Denmark”, “Kazan”] → []

# Процедуры:
1. size - получает строку, true если длинна меньше либо равна 3 символам
2. countsize - получает массив строк, возвращает количество элементов соответствующих условию.
3. show - выводит на экран переданный в нее массив

# Алгоритм.

1.Запрашиваем количество элементов в базовом массиве и вводим его через консоль.
2. Подсчитываем количество элементов нужной длинны и создаем новый массив с полученным количеством элементов.
3. Перебираем элементы базового массива, каждый элемент проверяем на соответствие условию, если подходит, копируем в результирующий массив.

![Это алгоритм](algo.jpg)