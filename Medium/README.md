# 1. How Much is True?

#### #arrays #language_fundamentals

## **Create a function which returns the number of `true` values there are in an array.**

### Examples

```js
countTrue([true, false, false, true, false]) ➞ 2

countTrue([false, false, false, false]) ➞ 0

countTrue([]) ➞ 0
```

### Notes

- Return 0 if given an empty array.
- All array items are of the type bool (`true` or `false`).

### Resources

- [Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [Array.prototype.reduce()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- [find() Method](https://www.w3schools.com/jsref/jsref_find.asp)

#### _Tarjima_

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
- Barcha massiv elementlari boolean(`true` yoki `false`) bo'ladi

---

# 2. A Redundant Function

#### #closures #functional_programming #language_fundamentals

## **Write a function** `redundant` **that takes in a string** `str` **and returns a function that returns**

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

#### _Tarjima_

# 2. Ortiqcha funksiya

## `str` **satrini qabul qiladigan va qaytaruvchi funksiyani qaytaruvchi ortiqcha funksiyani yozing**

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

---

# 3. RegEx Exercise: An empty string

#### #regex

### If you've completed this **RegEx** series from I to XXII then you have been exposed to all of **MDN**'s documentation on [regular expressions special characters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#Using_special_characters). You can check my Collections under **Basic Reg Ex** in my profile if you missed any. This next part of the series is to help solidify what you've learned. In order to save time I will be searching the web to find **regular expression** exercises to post here.

### You can test for empty string like this:

```js
"".length === 0 ➞ true
```
### Use a **regular expression** to test for an empty string.
```js
const REGEXP = /your solution/
REGEXP.test("") ➞ true
```
### Notes
- You can find the solution in the **Resources** tab.

#### *Tarjima*
# 3. RegEx mashqi: bo'sh string
### Agar siz ushbu **RegEx** seriyasini I dan XXII gacha tugatgan bo'lsangiz, unda siz MDN ning [muntazam iboralar maxsus belgilar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#Using_special_characters) bo'yicha barcha hujjatlari bilan tanishgansiz. To'plamlarimni o'tkazib yuborgan bo'lsangiz, profilimdagi **Basic Reg Ex** ostidan tekshirishingiz mumkin. Seriyaning keyingi qismi siz o'rgangan narsalarni mustahkamlashga yordam beradi. Vaqtni tejash maqsadida men bu yerga joylashtirish uchun **muntazam ifoda** mashqlarini topish uchun internetni qidiraman.

### Siz shunday bo'sh stringni sinab ko'rishingiz mumkin:
```js
const REGEXP = /your solution/
REGEXP.test("") ➞ true
```
### Bo'sh satrni tekshirish uchun **muntazam ifodadan** foydalaning.
```js
const REGEXP = /your solution/
REGEXP.test("") ➞ true
```
### Eslatmalar
- Yechimni **Resurslar** yorlig'ida topishingiz mumkin.