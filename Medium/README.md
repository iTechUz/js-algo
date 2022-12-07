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
---
### *Tarjima*
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