Данный проект выплнен студентом 3 курса Физического факультета Баландином Юрием в качестве профессионального задания для разработчиков. 

Этот проект является реализацией игры Жизнь на языке Python в формате Jupyter ноутбука. Список 
необходимых библиотек находится в файле requirements. Сам проект реализован в файле Life.ipynb. В нем 
можно задать размер поля и количество итераций (параметры n, iteraz). Начальную конфигурацию необходимо задать непосредственно 
в функции initial_state(n). Реализована возможность задать случайную конфигурацию (функция random_initial_state(n) и 
аргумент random = True в функции make_life()).В последней ячейке задана конигурация так называемого Долгожителя (R-пентамино).
С помощью библиотек визуализации развитие системы представлено в файле фората .gif, который появляется после выполнения фукнции make_life().
Для запуска кода необходимо последовательно выполнять ячейки кода, задавая при этом необходимые параметры. Последние три ячейки - 
примеры игры Жизнь с разными начальными состояниями (планер, случайное начальное состояние, долгожитель).
