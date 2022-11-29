**Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами**

##Решение

Два массива: в первом пользователь самостоятельно с клавиатуры вводит массив из строк через пробел. Второй массив получает длинну первого. Далее невозвращаемый метод с циклом внутри, который будет считать количество символов в каждом элементе массива и проверять их на условие "больше или равно трем". Подходящий элемент записывается во второй массив и count увеличивается на единицу пока цикл не переберет все элементы первого массива.