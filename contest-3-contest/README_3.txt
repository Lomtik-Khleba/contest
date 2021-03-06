Задача 03-1: НОД четырех
На вход программе подаются 4 натуральных числа не превосходящих 109. Требуется найти их наибольший общий делитель.

Примеры
Входные данные
1 2 3 4
Результат работы
1
Входные данные
2 4 6 8
Результат работы
2
Входные данные
3 9 27 4
Результат работы
1
Входные данные
9 18 27 6
Результат работы
3



Задача 03-2: Проще некуда
На вход программе подается натуральное число N, не превосходящее 109. Требуется найти наименьшее возможное простое число P, больше либо равное N.

Указание: реализуйте функцию isprime, проверяющую число на простоту.

Примеры
Входные данные
4
Результат работы
5
Входные данные
7
Результат работы
7


Задача 03-8: Итерированная медиана
Дан массив целых чисел нечетной длины N. По нему строится массив длины N-2 по следующему правилу: первый элемент нового массива равен медиане первого, второго и третьего элементов старого, второй элемент нового — медиане второго, третьего и четвертого элементов старого, и так далее. i-ый элемент нового массива равен медиане i-го, i+1-го и i+2-го.

Далее по новому массиву строится следующий массив длины N-4 по такому же правилу. Затем строится массив длины N-6, и так далее. Процесс продолжается до тех пор, пока не получится массив длины 1. Ваша задача определить, чему будет равен единственный элемент этого массива.

На стандартном потоке ввода задаётся нечетное натуральное число N (0 < N ≤ 1000), после которого следуют N целых чисел ai — элементы исходного массива (0 ≤ ai ≤ 106).

На стандартный поток вывода напечатайте единственное число — значение единственного элемента конечного массива.

Указание: в решении необходимо реализовать функцию, которая находит медиану трех чисел.

Примеры
Входные данные
5
1 2 3 4 5
Результат работы
3
Входные данные
5
3 4 5 1 2
Результат работы
4


Задача 03-9: Биссектрисы треугольника.
На вход программе подаются координаты вершин треугольника ABC (сначала координаты вершины A, затем B, затем C).

Выведите координаты пересечения биссектрисы ∠ACB со стороной AB, затем координаты точки пересечения биссектрисы ∠BAC со стороной BC, затем координаты точки пересечения биссектрисы ∠ABC со стороной AC. Все координаты выводите с точностью до 5 знаков после запятой.

Примеры
Входные данные
-1.0 -1.0
0 1
1.0 -1
Результат работы
-0.52786 -0.05573
0.52786 -0.05573
0.00000 -1.00000
Входные данные
-1 -1
1 0
-2 1
Результат работы
-0.17157 -0.58579
-0.50000 0.50000
-1.41421 -0.17157

Задача 03-13: Очень трудный день
Сегодня очень трудный день, так что ваша задача очень проста. Дано целое число N (1 ≤ N ≤ 14) и число K (1 ≤ K ≤ N). Требуется вывести в лексикографическом порядке все строго возрастающие последовательности длины K, состоящие из целых чисел от 0 до N-1.

Примеры
Входные данные
3 2
Результат работы
0 1
0 2
1 2
Входные данные
3 3
Результат работы
0 1 2
Входные данные
4 3
Результат работы
0 1 2
0 1 3
0 2 3
1 2 3


Задача 03-14: Лошадью ходи!
Толик и Гарик вечерами играют в несложную расслабляющую игру на шахматной доске.

Перед началом игры на доске на клетке A1 находится белый конь Толика. Гарик может поставить своего чёрного ферзя на любую из клеток, которая находится под боем белого коня Толика. После этого ходит Толик, который также может поставить своего коня на любую из клеток, которая находится под боем чёрного ферзя Гарика.

У Толика и Гарика ровно по одной фигуре, которые они переставляют, то есть новые фигуры на доске не появляются. На момент первого хода на доске только белый конь, на момент всех последующих на доске стоят обе фигуры.

В этой незамысловатой игре побеждает тот, кто поставит свою фигуру на клетку H8.

И Толик, и Гарик известны своей хитростью и часто жульничают. Единственное правило, которое они строго соблюдают, — выставлять фигуры на доску, а не рядом с ней (то есть поле I9 фигурировать в ходе не может). Помогите следящей за их игрой мировой общественности выяснить, по правилам ли была сыграна партия.

На стандартном потоке ввода задаётся последовательность ходов соперников.

Каждый ход записывается на отдельной строке в виде двух символов, обозначающих клетку, куда игрок переставляет свою фигуру. Первым всегда ходит Гарик (своим чёрным ферзём), далее ходы чередуются.

Запись ходов оканчивается заглавной латинской буквой X на отдельной строке, обозначающей, что предшествующий ход привёл одного из игроков на финишную клетку.

Требуется на стандартный поток вывода напечатать одно из следующих трёх слов. Если все ходы были сделаны по правилам, и игра закончилась победой Анатолия, выведите слово Tolik. Если в честном поединке победил Гарри, выведите слово Garik. Если какой-либо из ходов был сделан не по правилам или ни один из игроков не достиг финальной клетки, выведите слово Cheaters.

Указание: использовать массивы запрещается.

Указание: определите одну или несколько функций для проверки корректности очередного хода.

Примеры
Входные данные
C2
H7
F8
H8
X
Результат работы
Tolik
Входные данные
C2
D4
E6
F7
H8
X
Результат работы
Cheaters
Входные данные
B3
X
Результат работы
Cheaters


Задача 03-24: Фонарики
Полоска клетчатой бумаги 1xN описывается последовательностью из N чисел. Число 0 означает, что клетка пустая. Число K, отличное от нуля, означает, что в данной клетке лежит фонарик. Фонарик освещает |K| клеток слева от своей клетки, если K < 0, и справа от своей клетки, если K > 0. Фонарик не освещает свою клетку. Фонарик освещает клетку с другим фонариком, но не освещает клетки за другим фонариком (свет фонариков не распространяется за фонарики).

Опишите функцию int lighten(int N), которая считывает со стандартного потока ввода N чисел, описывающих полоску бумаги 1xN. Функция должна возвращать количество освещенных клеток на полоске.

Также напишите программу, демонстрирующую работу функции lighten. На вход программе подается число N, за которым следует N целых 32-битных чисел, описывающих полоску бумаги. N — натуральное, не превосходящее 10000. Программа должна выдавать единственное число — количество освещенных клеток.

Указание: использовать массивы запрещается.

Примеры
Входные данные
10
0 0 -3 0 2 0 -4 0 0 0
Результат работы
5
Входные данные
10
0 2 0 0 0 -2 0 4 0 0
Результат работы
5
