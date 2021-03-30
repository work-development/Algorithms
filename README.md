# Алгоритмы
Задачи по алгоритмам и структурам данных
 
## Основные структуры данных:  
**A. Кружки.** Вывод уникальных элементов по одному на строке, в порядке появления во входных данных.  
**B. Мониторинг.** Транспонирование матрицы  
**C. Подстроки.** Длина наибольшей подстроки, которая не содержит повторяющиеся символы  
**D. Соседи.** Дана матрица. Нужно написать функцию, которая для элемента возвращает всех его соседей.   
#### Односвязный список  (Linked List).     
Реализована структура данных список и вставка нового узла в список  
**E. Список дел.** Заполнение связного списка (данные подаются в обратном порядке)    
**F. Нелюбимое дело.** Удаление элемента из односвязного списка (ф-ция принимает на вход голову списка и номер удаляемого дела и возвращает голову обновлённого списка)  
**G. Заботливая мама.** Определение индекса первого вхождения передаваемого ей на вход значения в связном списке    
#### Двусвязный список (Doubly Linked Node).    
Реализована структура данных двусвязный список.   
**H. Все наоборот.**  Функция, которая вернёт двусвязный список в обратном порядке   
#### Стек (Stack).        
Реализована структура данных стек.  
**I. Стек - Max.** Реализация класса StackMax, который поддерживает операцию определения
максимума среди всех элементов в стеке.    
**J. Стек - MaxEffective.**  Реализация класса StackMaxEffective, поддерживающий операцию определения
максимума среди элементов в стеке. Сложность операции должна быть O(1). (Решение реализовано в задаче I)  
**K. Уникальный Стек.**  Реализация класса StackSet, который хранит только уникальные элементы.
При этом операция добавления элемента в стек выполняться за O(1).   
**L. Скобочная последовательность.** Дана скобочная последовательность. Нужно определить, правильная ли она.  
#### Очередь (Queue).        
**M. Очередь.**  Реализована структура данных очередь. Реализованы операции добавления, удаления, получения элемента, определение текущего размера,
и метод, показывающий, пуста ли очередь или нет. Очередь реализована на основе массива.  
**N. Ограниченная очередь.**  Реализован класс MyQueueSized(), который принимает параметр max_size,
означающий максимально допустимое количество элементов в очереди.  
**O. Шифрование.**  Число анаграмм шаблона в строке.  
**P. Списочная очередь.**  Реализована очередь, написанная с использованием связного списка.  
#### Дек (Dec).   
**Q. Дек.** Эффективная реализация дека. Все операции работают за O(1)   

## Проект по Структурам данных.     

**A. Калькулятор.**  В единственной строке дано выражение, записанное в обратной польской нотации. Производится вычисление выражения.  
**B. Циклы.** Программа определяет есть ли цикл в связном списке  

## Рекурсия.  

**Пример задачи на рекурсию.** Реализован алгоритм рекурсивного поиска файла во вложенных папках данной директории   
**A. Рекурсивные числа Фибоначчи.**  Рекурсивная реализация функции, определяющая по номеру значение n-ого числа Фибоначчи.  
**B. Фибоначчи с памятью.** Эффективная реализация задачи А (одни и те же значения повторно не вычисляются).    
**C. Эффективные числа Фибоначчи.** Эффективная реализация задачи B (Объем дополнительной памяти должен быть O(1)).  
**D. Последняя цифра.**  Вывод последней цифры в n - ом числе Фибоначчи  

#### Базовый и рекурсивный случай.    

**E. Кондратиева система шифрования.** Вычисление факториала   
**F. Циклический факториал.** Реализация факториала при помощи цикла    

#### Преимущества и недостатки рекурсии.  

**G. Недоалфавит.**  На вход подается маленькая буква английского алфавита. Нужно вывести ответ - алфавит с начала до заданной буквы - в строку через пробел.   
**H. Генератор скобок.**  Все возможные скобочные последовательности заданной длины.  
**I. Призы.**  В призовом фонде имеется n монет различного достоинства. Нужно определить, можно ли разделить
их между победителями таким образом, чтобы каждый получил одинаковую сумм.  
**J. Кондратиева Грамматика.**  Нужно вывести k-ый символ в n-ой строке. Следующая строка,получается из предыдущей, 0 -> 01, и каждую 1 -> 10.  
**K. Корень из двух.**  Вывод значения квадратного корня из двух с точностью 5 знаков после запятой.  

#### Хвостовая рекурсия.    

**L. Банкомат.**  Найти число способов, которым можно набрать нужную сумму используя заданные типы монет (количество монет каждого типа бесконечно).    
**M. Земельный участок.**  Дан прямоугольный участок. Найти максимально возможный размер квадратных участков.   
**N. Безупречные коэффициенты.**  НОД(x,y) = ax + by. Найти НОД(x,y) и a, b.   

#### Примеры задач на рекурсию.  

- Бинарный поиск.    
- Алгоритм быстрого возведения в степень.  
- Алгоритм генерации всех двоичных последовательностей длины n.  



