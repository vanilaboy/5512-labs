# ОСНОВНОЕ ЗАДАНИЕ:
Реализовать класс ParallelMatrixProduct для многопоточного умножения матриц UsualMatrix.
В конструкторе класс получает число потоков, которые будут использованы для перемножения (число потоков может быть меньше, чем число строк у первой матрицы).
В функции main сравнить время перемножения больших случайных матриц обычным и многопоточным способом. Получить текущее время можно с помощью методов класса System.


# ДОПОЛНИТЕЛЬНОЕ ЗАДАНИЕ:
Реализуйте многопоточную версию программы, которая вычисляет число способов поставить N ферзей на доске N на N, чтобы они не били друг друга. 
                  
    int calcQueenNum(int N, int treadNum)
 Подберите N так, чтобы `calcQueenNum(N, какое-то число > 1)` выигрывает по времени работы у `calcQueenNum(N, 1)` 
 
 __Hint:__ Первый поток отвечает за все комбинации, в которых ферзь в первом столбце находится на позиции 1....n/(число потоков)
 


