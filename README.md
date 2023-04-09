## Кратко ##
Подсчет количества выпуклых многоугольников с вершинами на ограниченной квадратной сетке.

## Задача ##
Пусть дана сетка с квадратными ячейками, размера n * n.

Многоугольник, у которого три вершины лежат на одной стороне выпуклым в подсчетах не считается (в коде это несложно меняется).
Многоугольники, отличающиеся сдвигом по сетке учитываются в подсчете один раз (изменить это несложно).
Многоугольники, отличающиеся поворотом или симметрией в подсчетах не считаются равными.

## Асимптотика ##
Алгоритм работает за O(n^4) времени и O(n^2) памяти, распараллелен. Подробнее в code/docs.md.

## Результаты ##
в data/ два файла:

square - количество многоугольников, которые можно разместить на сетке размера n * n.

accurate - количество многоугольников, которые можно можно вписать в сетку размера n * m, но нельзя в меньшую.