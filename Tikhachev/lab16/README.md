Задание 16.
Разработать сервлет, который показывает двухуровневый список. Список загружается из текстового файла на сервере, который имеет следующий формат:
* Звери
    * Волк
    * Корова
* Птицы
    * Курица
    * Орел
    * Попугай

Элементов первого и второго уровня может быть произвольное количество. Элементы списков второго уровня смещены на 4 пробела вправо. 

Реализовать интерфейс для удобной работы со списком на javascript (js). При выводе в виде html список верхнего уровня становится нумерованным. 
Около каждого элемента первого уровня выводится символ, при нажатии на который скрываются или показываются элементы соответствующего списка второго уровня.
 Если список второго уровня показан, то выводится символ "-", позволяющий скрыть список. Если список второго уровня скрыт, то выводится символ "+", позволяющий показать список.

Исходное состояние:
1. Звери [+]
2. Птицы [+]

Состояние после нажатие на "+" около пункта Птицы:
1. Звери [+]
2. Птицы [-]
    * Курица
    * Орел
    * Попугай


При скрытии и показе списка не должно быть запросов на сервер. Графический интерфейс обеспечивает программа на js, выполняющаяся внутри браузера.
Доп задание
Добавить форму для добавления элементов в списки. При добавлении элемента в отдельных полях указывается: номер списка первого уровня и название 
нового пункта. Если в качества номера списка первого уровня указан номер “0”, то новый список первого уровня. Реализовать с помощью js проверку, что
количество символов в новом элементе списка не больше 10 (иначе выдается ошибка).
Список, в который добавляется пункт, существует


