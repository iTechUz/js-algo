# 1. How Much is True?

#### #arrays #language_fundamentals

## **Create a function which returns the number of ``true`` values there are in an array.**

### Examples
```js
countTrue([true, false, false, true, false]) ➞ 2

countTrue([false, false, false, false]) ➞ 0

countTrue([]) ➞ 0
```
### Notes
- Return 0 if given an empty array.
- All array items are of the type bool (``true`` or ``false``).

### Resources
- [Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [Array.prototype.reduce()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- [find() Method](https://www.w3schools.com/jsref/jsref_find.asp)

#### *Tarjima*
# Qanchalik haqiqat?
## **Massivdagi haqiqiy qiymatlar sonini qaytaruvchi funksiya yarating.**
### Misollar
```js
countTrue([true, false, false, true, false]) ➞ 2

countTrue([false, false, false, false]) ➞ 0

countTrue([]) ➞ 0
```
### Eslatmalar
- Agar bo'sh massiv berilgan bo'lsa, 0 ni qaytaring
- Barcha massiv elementlari boolean(``true`` yoki ```false```) bo'ladi
---
# 2. A Redundant Function
#### #closures #functional_programming #language_fundamentals
## **Write a function** ``redundant`` **that takes in a string** ``str`` **and returns a function that returns**
### Examples
```js
const f1 = redundant("apple")
f1() ➞ "apple"

const f2 = redundant("pear")
f2() ➞ "pear"

const f3 = redundant("")
f3() ➞ ""
```
### Notes
- Your function should return a **function**, not a string.
### Resources
- [Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
- [Understanding Closures in JavaScript](https://blog.bitsrc.io/a-beginners-guide-to-closures-in-javascript-97d372284dda)
- [JavaScript Function Closures](https://www.w3schools.com/js/js_function_closures.asp)

#### *Tarjima*
# 2. Ortiqcha funksiya
## ``str`` **satrini qabul qiladigan va qaytaruvchi funksiyani qaytaruvchi ortiqcha funksiyani yozing**
### Misollar
```js
const f1 = redundant("apple")
f1() ➞ "apple"

const f2 = redundant("pear")
f2() ➞ "pear"

const f3 = redundant("")
f3() ➞ ""
```
### Eslatmalar
- Sizning funktsiyangiz satrni emas, balki **funktsiyani** qaytarishi kerak