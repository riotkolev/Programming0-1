# Задачи с констуркцията If-Elif-Else

## Задача 1 - Легални по американски.

Във файл, който се казва `legal.py`, напишете програма, която прави следното:

* Чете от потребителя число, което отговаря на годините му.
* Ако годините са `>= 21`, му казва, че е легален.
* Иначе му казва, че е нелегален!

**Примерно използване:**

```
You age? 18
Your are illegal here.
```

```
Your age? 21
You are legal here.
```

## Задача 2 - Игра на Зарове.

Във файл, който се казва `dice_game.py`, напишете програма, която прави следното:

* Чете от потребител едно число `N`, което ще е броят на страните на зара
* Чете името на първия играч.
* Чете името на втория играч.
* Хвърля зарове за първия и втория играч.

Имаме следните условия:

* Играчът с по-голямо число, побежадава в играта. Програмата трябва да отпечата името на победителя"
* Ако хвърлят едно и също число, програмата казва, че има равенство.

**Примерно използване:**

```
Enter dice side: 10
Enter player1 name: Rado
Enter player2 name: Ivo
Rado rolls 10
Ivo rolls 1
Rado wins!
```

## Задача 3 - Калкулатор

Във файл, който се казва `calculator.py`, напишете следната програма:

* Чете от потребител, първото число `a`
* Чете от потребител, второто число `b`
* Чете от потребител, операцията `oper`, която може да е или `+`, `-`, `*`, и `/`.

Програмата трябва да направи следното нещо:

* Изкарва на екрана резултатът от получения израз: `a oper b`.
* Ако получи неизвестна операция, да каже за това.


**Примерно използване:**

```
Enter a: 5
Enter b: 10
Enter operation: +
Result is:
15
```

или

```
Enter a: 5
Enter b: 10
Enter operation: ^^
We do not support that operation.
```

## Задача 4 - Сравнение на числа

Във файл, който се казва `compare.py`, напишете следната програма:

* Чете две числа от потребителя.

И спрямо следните условия, казва:

* Кое от двете числа е по-голямо?
* Ако са равни, казва, че числата са равни.

Примерно използване:

```
Enter a: 5
Enter b: 6
b(6) is bigger than a(5)!
```

или:

```
Enter a: 5
Enter b: 5
a(5) is equal to b(5)
```

## Задача 5 - Четно или нечетно?

Във файла `evenodd.py`, напишете програма, която:

* Чете от потребителя дадено число
* Отпечатва на екрана дали това число е четнои ли нечетно.

**Едно число е четно (even), ако се дели на 2 без остатък. Иначе е нечетно (odd).**

Примерно използване:

```
Enter number: 5
5 is odd.
```

```
Enter number: 4
4 is even.
```

## Задача 6 - Is it friday yet?

Ще направим нещо подобно на това - http://isitfridayyet.org/

В файла `friday.py` имате следния код:

```python
import time

today = time.strftime("%A")

print(today)
```

Имате следната задача:

1. Разберете какво прави този код. Пуснете файла и експериментирайте!
2. Допишете код към файла, така че ако е петък, да изпише `It is friday!`
3. Ако не е петък - да напише `It is not friday ;( Today is ......`, като на мястото на `......` да пише днешния ден.

**Примерно използване:**

```
It is not friday ;( Today is Monday.
```
