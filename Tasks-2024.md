## Задание 1. Генераторы и python

1. Сгенерировать случайный граф своего типа, 4х разных размеров от 100 тыс. вершин, 3х видов плотности. Проверить, как при изменении числа вершин и ребер графа изменяются его характеристики:
- связность, размер компоненты сильной связности, размер компоненты слабой связности
- диаметр
- длина среднего кратчайшего пути 
- распределение степеней
- средний коэффициент кластеризации
Сделать выводы.
2. Построить график распределения степеней для 2х графов из набора. Сделать выводы.

3. Построить картинку случайного графа своего типа, но маленького размера. 

4. Сдать: py / ipynb файл, выводы можно написать в комментариях. Срок сдачи - до 15 ноября.

Тип своего графа см. в таблице. Использовать networkx, igraph или networkit (python).

Пример для networkx: https://habr.com/ru/articles/516514/ 

Пример для igraph https://github.com/annapirova/graph_course_unn/blob/main/igraph_examples/python/igraph_generate.py 


## Задание 2. С++ библиотека

Цель задания: изучить готовую параллельную библиотеку для работы с графами. "Свою" библиотеку см. в таблице. Нужно написать небольшую программу или использовать готовый example из библиотеки, который:
1. Считывает граф из файла (графы берем из Suite Sparse matrix collection или SNAP).
2. Запускает для графа 1-2 задачи (задачи выбираем сами со 2го листа таблицы, желательно разные).
3. Изучить, как в библиотеке хранится граф, есть ли какие-то общие функции, которые используются для реализации всех алгоритмов (например, фильтрация вершин / ребер, построение подмножества и т.п.)
4. Изучить, как в этой библиотеке реализованы эти задачи, какой алгоритм, какие приемы оптимизации использвались.
5. Провести вычислительные эксперименты на кластере (когда будет к нему доступ).
6. Подготовить небольшой доклад о библиотеке (можно объединиться): как устроена, как ей пользоваться. Срок - первый доклад ~22 ноября.

P.S. Все библиотеки должны работать на Linux, на Windows можно не пытаться их собрать. Если будут проблемы со сборкой GBBS, ее можно заменить на SuiteSparse::GraphBLAS. Когда выберете для себя алгоритм, впишите в таблицу.


## Задание 3. Тестирование

Будет модификация этого задания: https://github.com/annapirova/graph_course_unn/blob/main/Testing.md