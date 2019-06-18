# Software Craftsmanship - Test Driven Development

## Źródło

Zadanie powstało na podstawie https://github.com/testdouble/contributing-tests/wiki/Greeting-Kata

## Zadanie

Wykorzystać podejście test driven development (https://www.samouczekprogramisty.pl/test-driven-development-na-przykladzie/) podczas implementowania metody 
```
String greet(String name)
```
zgodnie z kolejnymi wymaganiami: 
* dla podanego parametru name, np. `Bob` metoda powinna zwrócić `Hello, Bob.`,
* jeżeli podany parametr jest równy `null`, to należy zwrócić `Hello, my friend`,
* jeżeli podane imię jest pisane dużymi literami, bp. `BOB`, to należy zwrócić `HELLO BOB!` (tym razem bez przecinka),
* jeśli podano dwa parametry np. `Jill`, `Jane`, to metoda powinna zwrócić `Hello, Jill and Jane`, można wykorzystać varargs, tablicę lub listę,
* jeśli podano dowolną liczbę imion, np. `Jill`, `Jane`, `Bob`, to należy zwrócić `Hello, Jill, Jane and Bob` (początkowe imiona rozdzielone są przecinkami, a ostatnie `and`).

