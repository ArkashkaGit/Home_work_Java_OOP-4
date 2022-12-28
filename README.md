# Объектно-ориентированное программирование
## на основе языка JAVA
## Home work 4

![java.jpg](java.jpg)


1. _Создайте интерфейс IsGood<T>. 
Внутри него содержится единственная функция:
boolean isGood (T item);
Смысл этого интерфейса: 
ему дают элемент, он его одобряет или не одобряет._

2. _Создайте следующие детские классы:_
>- __IsEven — ему дают целое число, 
он одобряет его, если оно чётное__
>- __IsPositive — ему дают целое число, 
он одобряет его, если оно положительное__
>- __BeginsWithA — ему дают строку, он одобряет её,
если она начинается с буквы A__
>- __BeginsWith — в конструкторе запоминает строку. 
Ему дают строку, он проверяет, 
что она начинается с того, что он запомнил__

3. _Создайте обобщённую функцию filter. 
Ей дают любую коллекцию любого типа, 
и одобрятель IsGood.
Функция возвращает новую коллекцию, 
куда входят только одобренные элементы из коллекции.
Продемонстрируйте, что это работает._