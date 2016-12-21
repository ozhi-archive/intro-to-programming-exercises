#Малко побитови операции

[Bitwise operations](https://en.wikipedia.org/wiki/Bitwise_operation)

[Bit manipulation](https://en.wikipedia.org/wiki/Bit_manipulation)

###[Задача 1.]()
Функция `bool getXthBitOfN(int n, int x)`, която връща __x__тия бит на числото __n__.

Стандартно битовете в числата се номерират от 0 отдясно наляво. Така __i__ят бит отговаря на __i__тата степен на двойката и лесно правим преобразуване между десетична и двоична бройна система.



###[Задача 2.]()
Функция `void setXthBitOfN(int &n, int x, bool value)`, която променя стойносттна на __x__я бит на числото __n__ на __value__.

Забележете, че подаваме __n__ по референция, а не по стойност, защото искаме промяната върху __n__ да се отрази и върху фактическия параметър, с който е извикана функцията.

Друг вариант би бил функцията да не е `void`, а да връща новата стойност на __n__.



###[*Задача 3.]()
Функция `void printAllSubsets(int a[], int length)`, която приема масив, предствляващ множество от цели числа и неговата дължина и извежда на екрана разделени на нов ред всички подмножества на това множество.



###[Решения](solutions.cpp)