# Алгоритмы
Задачи по алгоритмам и структурам данных
 
## Основные структуры данных.  
**A. Кружки.** Вывод уникальных элементов по одному на строке, в порядке появления во входных данных.  
**B. Мониторинг.** Транспонирование матрицы  
**C. Подстроки.** Длина наибольшей подстроки, которая не содержит повторяющиеся символы  
**D. Соседи.** Дана матрица. Нужно написать функцию, которая для элемента возвращает всех его соседей.   
### Односвязный список  (Linked List).     
Реализована структура данных список и вставка нового узла в список  
**E. Список дел.** Заполнение связного списка (данные подаются в обратном порядке)    
**F. Нелюбимое дело.** Удаление элемента из односвязного списка (ф-ция принимает на вход голову списка и номер удаляемого дела и возвращает голову обновлённого списка)  
**G. Заботливая мама.** Определение индекса первого вхождения передаваемого ей на вход значения в связном списке    
### Двусвязный список (Doubly Linked Node).    
Реализована структура данных двусвязный список.   
**H. Все наоборот.**  Функция, которая вернёт двусвязный список в обратном порядке   
### Стек (Stack).        
Реализована структура данных стек.  
**I. Стек - Max.** Реализация класса StackMax, который поддерживает операцию определения
максимума среди всех элементов в стеке.    
**J. Стек - MaxEffective.**  Реализация класса StackMaxEffective, поддерживающий операцию определения
максимума среди элементов в стеке. Сложность операции должна быть O(1). (Решение реализовано в задаче I)  
**K. Уникальный Стек.**  Реализация класса StackSet, который хранит только уникальные элементы.
При этом операция добавления элемента в стек выполняться за O(1).   
**L. Скобочная последовательность.** Дана скобочная последовательность. Нужно определить, правильная ли она.  
### Очередь (Queue).        
**M. Очередь.**  Реализована структура данных очередь. Реализованы операции добавления, удаления, получения элемента, определение текущего размера,
и метод, показывающий, пуста ли очередь или нет. Очередь реализована на основе массива.  
**N. Ограниченная очередь.**  Реализован класс MyQueueSized(), который принимает параметр max_size,
означающий максимально допустимое количество элементов в очереди.  
**O. Шифрование.**  Число анаграмм шаблона в строке.  
**P. Списочная очередь.**  Реализована очередь, написанная с использованием связного списка.  
### Дек (Dec).   
**Q. Дек.** Эффективная реализация дека. Все операции работают за O(1)   

## Проект: Структуры данных.     

**A. Калькулятор.**  В единственной строке дано выражение, записанное в обратной польской нотации. Производится вычисление выражения.  
**B. Циклы.** Программа определяет есть ли цикл в связном списке  

## Рекурсия.  

**Пример задачи на рекурсию.** Реализован алгоритм рекурсивного поиска файла во вложенных папках данной директории   
**A. Рекурсивные числа Фибоначчи.**  Рекурсивная реализация функции, определяющая по номеру значение n-ого числа Фибоначчи.  
**B. Фибоначчи с памятью.** Эффективная реализация задачи А (одни и те же значения повторно не вычисляются).    
**C. Эффективные числа Фибоначчи.** Эффективная реализация задачи B (Объем дополнительной памяти должен быть O(1)).  
**D. Последняя цифра.**  Вывод последней цифры в n - ом числе Фибоначчи  

### Базовый и рекурсивный случай.    

**E. Кондратиева система шифрования.** Вычисление факториала   
**F. Циклический факториал.** Реализация факториала при помощи цикла    

### Преимущества и недостатки рекурсии.  

**G. Недоалфавит.**  На вход подается маленькая буква английского алфавита. Нужно вывести ответ - алфавит с начала до заданной буквы - в строку через пробел.   
**H. Генератор скобок.**  Все возможные скобочные последовательности заданной длины.  
**I. Призы.**  В призовом фонде имеется n монет различного достоинства. Нужно определить, можно ли разделить
их между победителями таким образом, чтобы каждый получил одинаковую сумм.  
**J. Кондратиева Грамматика.**  Нужно вывести k-ый символ в n-ой строке. Следующая строка,получается из предыдущей, заменами 0 -> 01 и 1 -> 10.  
**K. Корень из двух.**  Вывод значения квадратного корня из двух с точностью 5 знаков после запятой.  

### Хвостовая рекурсия.    

**L. Банкомат.**  Найти число способов, которым можно набрать нужную сумму используя заданные типы монет (количество монет каждого типа бесконечно).    
**M. Земельный участок.**  Дан прямоугольный участок. Найти максимально возможный размер квадратных участков.   
**N. Безупречные коэффициенты.**  НОД(x,y) = ax + by. Найти НОД(x,y) и a, b.   

### Примеры задач на рекурсию.  

- Бинарный поиск.    
- Алгоритм быстрого возведения в степень.  
- Алгоритм генерации всех двоичных последовательностей длины n.   

## Жадные алгоритмы.  

**A. Расписание.**  Дано расписание предметов. Нужно составить расписание, в соответствии с которым
в классе можно будет провести как можно больше уроков.   
**B. Биржа.** Дан массив цен акций. На i-й позиции массива — цена в i-й день. Акции можно покупать и продавать, но 
только по одной штуке. В одно время не должно быть более одной открытой транзакции. Какую максимальную прибыль она может получить.   
**C. Подпоследовательность.** Даны 2 строки, и нужно понять, является ли первая из них подпоследовательностью второй.     
**D. Ценный рюкзак.** В n строках записано по 2 числа, разделенные пробелом: стоимость предмета и его вес. Найти те предметы, 
которыми можно было наполнить рюкзак т.ч. его стоимость была максимальной.   
**E. Печеньки.** К Васе в гости пришли одноклассники. Его мама решила угостить ребят печеньем. Печенья могут быть разного размера. 
У каждого ребёнка есть фактор жадности — минимальный размер печенья, которое он возьмёт. Нужно выяснить, сколько ребят останутся довольными.   
**F. Отсортированные строки.** Дан набор строк одинаковой длины, состоящих из маленьких латинских букв. Нужно определить, какое минимальное число позиций
в каждой из строк нужно удалить, чтобы буквы в строках, соответствующие каждому индексу из оставшихся, были лексикографически отсортированы по неубыванию.   
**G. Закручивающаяся спираль.** В n строках записано по m чисел. Нужно вывести на печать по спирали элементы матрицы: начиная с левого верхнего угла вправо.    
**H. Возрастающий подмассив.** Найти длину наибольшего возрастающего подмассива.   
**I. Одинаковые суммы.** Определить, возможно ли разделить массив на две части так чтобы суммы элементов в них были одинаковыми   
**K. Ипотека.** Дан массив из стоимостей домов и фиксированная сумма. Нужно определить какое максимальное количество домов можно приобрести на данную сумму.   
**L. Лестница** Для каждой ступеньки известно, на какое максимальное количество ступенек вверх с неё можно допрыгнуть. 
Нужно помочь Евлампии определить, сможет ли она добраться с нижней ступеньки на верхнюю.   

## Проект: Жадные алгоритмы и Рекурсия.  

**A. Фотокопии.**  Всего есть N датацентров c разной вместимостью в шт. фотографий. Каждую фотографию нужно хранить в двух экземплярах. Нужно вывести число, равное максимальному количеству фотографий, для которых можно хранить копии в этих датацентрах.   
**B. Поиск в сломанном массиве.**  Данные имеют 1 "дефект" в сортировке. Необходимо найти индекс требуемого элемента.   

## Сортировки.

### Квадратичные сортировки.

**A. Пузырек.** Реализация алгоритма пузырьковой сортировки.   
**B. Сортировка вставками.** Реализация алгоритма сортировки вставкой.    

### Быстрая сортировка.   

**C. Эффективная быстрая сортировка.** Оптимизация алгоритма быстрой сортировки. Алгоритму не требоваться O(n) дополнительной памяти.   
**D. Тараканьи бега.** Дано два не отсортированных списка. Требуется найти повторяющиеся числа и вывести их в порядке,
в котором они встречались в первом списке. (Квадратичная сортировка слишком медленна для этого)   
**E. Бессовестные тараканы.** Модификация задачи D: нужно в строку вывести числа с учетом того, как они записаны в первом списке.    
**F. Сортировка по четности.** Дан список чисел. Необходмо его отсортировать так, чтобы четные числа стояли
на четных позициях, а нечетные числа - на нечетных.   
**G. Периметр треугольника.** Дан массив целых чисел, в котором каждый элемент обозначает длину стороны треугольника. Нужно определить
максимально возможный периметр треугольника, составленного из сторон с длинами из заданного массива.   
**H. Клумбы.** Дан список отрезков. Вывести список компонент связности в отсортированном порядке.  
**I. Гардероб.** Дан список чисел. Необходимо уплотнить его в отсортированном порядке.   
**J. Относительная сортировка.** С помощью образца - массива уникальных чисел, задается порядок. В соответствии с этим порядком должны сортироваться числа.
Числа не входящие в образец нужно выводить в конце в соответствии со стандартной сортировкой.   
**K. Частичная сортировка.** Дан список чисел. Нужно разбить данные на максимально возможное количество частей таким образом, чтобы можно было отсортировать
каждую из частей отдельно, соединить, и при этом результат будет отсортирован. После сортировки отдельных частей менять части местами нельзя.    
**M. Самое длинное подслово.** Дана комбинация букв. Найти в ней максимально длинное слово из словарика.   
**N. Техника скорочтения.**  Сортировка матрицы по диагонали.   

### Алгоритм сортировки слиянием для связного списка.   
Реализован алгоритм сортировки слиянием для связного списка.   

## Проект: Сортировка.    

**A. Большое число.**  Даны числа. Нужно определить, какое самое большое число можно из них составить.   
**B. Radix Sort.**  Реализация алгоритма поразрядной сортировки.  

## Хеш.    

**A. Счастливый билет.**  Дано число. С этим числом производят преобразования: заменяют каждую цифру числа её второй степенью,
складывают получившиеся значения, повторяют алгоритм для результата предыдущего шага. Станет ли это число после данных преобразований равным 1?      
**B. Легкие числа.** Количество простых чисел меньше заданного.      
**C. Анаграммная группировка.** Дан перечень слов. Нужно вывести списки индексов слов являющиеся анаграммами.     
**D. Строковые числа.** Выведите строковое представление результата вычисления выражения a/b. Если при делении двух чисел получается периодическая дробь, нужно вывести период в скобках.     
**E. Соревнование** Поиск максимального числа подряд идущих раундов, по результатам которых получается ничья.      
**F. Странное сравнение.** Даны две строки. Нужно определить существует ли между этими строками изоморфизм, заданный заменой букв.     
**G. МногоГоша.** Дана строка, состоящая из заданных букв. Нужно найти все подстроки длины 10, которые встречаются более одного раза.      
**H. Общий подмассив.** Дано два массива чисел. Определить максимальную длину подстроки лежащую в пересечении множества подстрок.     
**I. Полиномиальный хеш.**  Реализована функция, вычисляющая полиномиальный хеш строки.     
**L. Сумма четверок.** Дан массив чисел и целевое число. Нужно вывести все множества четверок чисел из массива в сумме дающие целевое число.      
**M. Проверка паттерна.** Необходимо проверить текст на соответствие некоторому паттерну, который задан в виде последовательности букв. Между буквами
паттерна и словами текста должно устанавливаться взаимно однозначное соответствие при сохранении порядка букв паттерна и слов текста.         
**N. Самый длинный палиндром.** Необходимо узнать, палиндром какой наибольшей длины можно составить из букв данной строки.     
**O. Периметр.** На клетчатом поле из нулей нарисована некоторая односвязная фигура из единичек. Найдите периметр этой фигуры, каждая сторона клетки имеет длину 1.       
**P. Собери словарь.** Собирается словарь из двух списков.       

## Проект: Хеш.     
 
**A. Укоротитель урлов.** Есть два вида запросов: post url content и get url. Для запросов post нужно вернуть укороченный урл, для запросов
get - контент или сообщение error.   
**B. Хеш-таблица.** Реализация хеш-таблицы.   

## Деревья.   

- Обход в глубину.
- Обход в ширину.

**A. Бриллианты.** Найти максимальный вес узла.  
**B. Сбалансированное дерево.** Написать функцию, которая определяет, сбалансировано ли дерево.   
**C. Генеалогическое древо.** Вывести списки весов уровней графа.   
**D. Дерево - анаграмма.** Напишите функцию, которая определяет, является ли дерево анаграммой.   
**E. Деревья - близнецы.** Определить, являются ли деревья одинаковыми.   
**F. Вид слева.** Напчечатать список весов вершин дерева, расположенных слева.   
**G. Минимальные суммы.** Даны 2 массива, отсортированные по неубыванию, а также число k. Нужно определить k пар,
которые имеют наименьшую сумму.    
**H. Разность треш-индексов.** Выведите k - ую минимальную разницу между парами чисел в массиве.   
**I. Дерево поиска.** Написать функцию, которая определяет, является ли заданное дерево деревом поиска.  
**J. Максимальная глубина.** Найти максимальное число вершин в дереве, которое нужно преодолеть, чтобы добраться из корня дерева в любую наперед заданную вершину.   
**K. Числовые пути.** Дано дерево, в узлах которого записаны цифры от 0 до 9. Таким образом, каждый путь от корня до листа содержит число, 
получившееся конкатенацией цифр пути. Нужно найти сумму всех таких чисел в дереве.   
**L. Числа Кондроначчи.** Нужно вывести n - ое число Кондроначчи. Это последовательность, которая сформирована по такому правилу. 
Первое число равно 1. Далее следуют по возрастанию числа, простые множители которых принадлежат только множеству 2, 3, 5.   

## Проект: Деревья.   

**A. Кондратиева пирамида.** Нужно отсортировать данные так, чтобы они удовлетворяли следующим требованиям: Если сумма набранных очков участника 
A больше, чем у участника В, то А должен идти в списке раньше. При подсчете суммы нужно учитывать только положительные значения очков.
Если суммы равны, то первым должен идти участник, чье имя лексикографически меньше. При совпадении имен раньше должен идти участник, 
который во входных данных находится позже. При этом, если из имени участника можно составить английский вариант имени Кондратий
(например, если имя nekondratiy или drkonxxxiyatt), то все правила отменяются. Он должен идти в списке раньше. Если таких участников больше одного, 
то раньше должен идти тот, кто находится позже во входных данных. (Заработанные очки не рассматриваются).   


   


 


 


