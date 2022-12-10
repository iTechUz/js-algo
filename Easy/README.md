# 1. Bitwise Operations

`#bit_operations #language_fundaments #logic`

A decimal number can be represented as a sequence of bits. To illustrate:**

```js
6 = 00000110
23 = 00010111
```

From the bitwise representation of numbers, we can calculate the bitwise AND, bitwise OR and bitwise XOR. Using the example above:**
```js
bitwiseAND(6, 23) ➞ 00000110

bitwiseOR(6, 23) ➞ 00010111

bitwiseXOR(6, 23) ➞ 00010001
```

Write three functions to calculate the bitwise AND, bitwise OR and bitwise XOR of two numbers.**

**Examples**

```js
bitwiseAND(7, 12) ➞ 4

bitwiseOR(7, 12) ➞ 15

bitwiseXOR(7, 12) ➞ 11
```
**Notes**

  JavaScript has a useful function: toString(2), where you can see the binary representation of a decimal number.

  **Resources**
 - [Bitwise Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)
 - [Bitwise Operators](https://www.youtube.com/watch?v=mesu75PTDC8)
 - [String.prototype.padStart()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart?retiredLocale=de)

------------
**TARJIMA**

# 1. Bitli operatsiyalar

`#bit_operatsiyalar #til_asoslari #mantiq`

O'nlik sonni bitlar ketma-ketligi sifatida ko'rsatish mumkin. Misol uchun:**

``` js
6 = 00000110
23 = 00010111
```

Raqamlarning bit bo'yicha ko'rinishidan biz bit bo'yicha VA, bit bo'yicha OR va bit bo'yicha XOR ni hisoblashimiz mumkin. Yuqoridagi misoldan foydalanish:**
``` js
bitwiseAND(6, 23) ➞ 00000110

bitwiseOR(6, 23) ➞ 00010111

bitwiseXOR(6, 23) ➞ 00010001
```

Ikki raqamning bit yoʻnalishi boʻyicha VA, bit yoʻnalishi boʻyicha OR va bit boʻyicha XOR larini hisoblash uchun uchta funktsiyani yozing.**

**Misollar**

``` js
bit boʻyichaVA(7, 12) ➞ 4

bitwiseOR(7, 12) ➞ 15

bitwiseXOR(7, 12) ➞ 11
```
**Eslatmalar**

  JavaScript foydali funksiyaga ega: toString(2), bu yerda siz oʻnlik sonning ikkilik koʻrinishini koʻrishingiz mumkin.

  **Resurslar**
 - [Bitwise Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)
 - [Bitwise operatorlari](https://www.youtube.com/watch?v=mesu75PTDC8)
 - [String.prototype.padStart()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart?retiredLocale=de)

-------
# 2. Add up the Numbers from a Single Number

`#algoritms #math #number #resucion`

Create a function that takes a number as an argument. Add up all the numbers from 1 to the number you passed to the function. For example, if the input is 4 then your function should return 10 because 1 + 2 + 3 + 4 = 10.

**Examples**

```js
addUp(4) ➞ 10

addUp(13) ➞ 91

addUp(600) ➞ 180300
```

**Notes**

- Expect any positive number between 1 and 1000.

**Resources**
 - [1 + 2 + 3 + 4 + ⋯](https://en.wikipedia.org/wiki/1_%2B_2_%2B_3_%2B_4_%2B_%E2%8B%AF)
 - [Techniques for Adding the Numbers 1 to 100](https://betterexplained.com/articles/techniques-for-adding-the-numbers-1-to-100/)
 - [For Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)

-------------
**TARJIMA**

# 2. Bitta raqamdan raqamlarni qo'shing

` #algoritmlar #matematik #raqam #qayta chiqarish `

Argument sifatida raqamni oladigan funksiya yarating. 1 dan funktsiyaga o'tgan raqamgacha bo'lgan barcha raqamlarni qo'shing. Misol uchun, agar kirish 4 bo'lsa, sizning funktsiyangiz 10 ni qaytarishi kerak, chunki 1 + 2 + 3 + 4 = 10.

**Misollar**

``` js
addUp(4) ➞ 10

addUp(13) ➞ 91

addUp(600) ➞ 180300
```

**Eslatmalar**

- 1 dan 1000 gacha bo'lgan har qanday ijobiy raqamni kuting.

**Resources**
 - [1 + 2 + 3 + 4 + ⋯](https://en.wikipedia.org/wiki/1_%2B_2_%2B_3_%2B_4_%2B_%E2%8B%AF)
 - [1 dan 100 gacha raqamlarni qo'shish texnikasi](https://betterexplained.com/articles/techniques-for-adding-the-numbers-1-to-100/)
 - [Loop uchun](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)

------------
# 3.Matchstick Houses

`#algebra #logiv #math`

This challenge will help you interpret mathematical relationships both algebraically and geometrically.

Matchstick Houses, Steps 1, 2 and 3

Create a function that takes a number (step) as an argument and returns the number of matchsticks in that step. See step 1, 2 and 3 in the image above.

**Examples**

```js
matchHouses(1) ➞ 6

matchHouses(4) ➞ 21

matchHouses(87) ➞ 436
```
**Notes**

- Step 0 returns 0 matchsticks.
- The input (step) will always be a non-negative integer.
- Think of the input (step) as the total number of houses that have been connected together.

**Resources**
- [Matchstick Patterns](https://www.transum.org/Maths/Activity/Matchstick_Patterns/)
- [Conditional Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)
- [JavaScript Math Object](https://www.w3schools.com/Js/js_math.asp)
- --------------
# 3. Gugurt uylari

`#algebra #logiv #matematika'`

Bu vazifa matematik munosabatlarni ham algebraik, ham geometrik jihatdan izohlashga yordam beradi.

Gugurt uylari, 1, 2 va 3-bosqichlar

Argument sifatida raqam (qadam) oladigan va shu bosqichda gugurt tayoqlari sonini qaytaradigan funksiya yarating. Yuqoridagi rasmdagi 1, 2 va 3-bosqichlarga qarang.

**Misollar**

``` js
Gugurt uylari(1) ➞ 6

Gugurt uylari(4) ➞ 21

Gugurt uylari(87) ➞ 436
```
**Eslatmalar**

- 0-bosqich 0 ta gugurt tayoqchasini qaytaradi.
- Kirish (qadam) har doim manfiy bo'lmagan butun son bo'ladi.
- Kirish (qadam) ni bir-biriga ulangan uylarning umumiy soni sifatida tasavvur qiling.

**Resurslar**
- [Matchstick Patterns](https://www.transum.org/Maths/Activity/Matchstick_Patterns/)
- [Shartli operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)
- [JavaScript Math Object](https://www.w3schools.com/Js/js_math.asp)