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

# 1. Qanchalik haqiqat?

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
---

# 4. Tile Teamwork Tactics
#### ``#conditions #language_fundamentals #numbers #validation``
### In a board game, a piece may advance 1-6 tiles forward depending on the number rolled on a six-sided dice. If you advance your piece onto the **same tile** as another player's piece, both of you earn a bonus.
### Can you reach your friend's tile number in the next roll? Create a function that takes your position ``a`` and your friend's position ``b`` and returns a boolean representation of whether it's possible to earn a bonus on any dice roll.
### Examples
```js
possibleBonus(3, 7) ➞ true

possibleBonus(1, 9) ➞ false

possibleBonus(5, 3) ➞ false
```
### Notes
- You cannot move backward (which is why example #3 doesn't work).
- If you are already on the same tile, return ``false``, as you would be advancing away.
- Expect only positive integer inputs.
### Resources
- [Logical AND (&&)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND)
- [Greater than or equal (>=)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Greater_than_or_equal)
- [Less than or equal (<=)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Less_than_or_equal#:~:text=The%20less%20than%20or%20equal,right%20operand%2C%20and%20false%20otherwise.)
#### *Tarjima*

# 4. Plitkalar bilan ishlash tatikasi

### Stol o'yinida bir parcha olti qirrali zarga tashlangan raqamga qarab 1-6 plitka oldinga siljishi mumkin. Agar siz o'z buyumingizni boshqa o'yinchining **buyumiga o'xshatib qo'ysangiz**, ikkalangiz ham bonus olasiz.

### Keyingi rolikda do'stingizning plitka raqamiga kira olasizmi? Sizning ``a`` pozitsiyangizni va do'stingizning ``b`` o'rnini egallaydigan funksiya yarating va istalgan zarda bonus olish mumkinmi yoki yo'qligini ko'rsatuvchi mantiqiy ifodani qaytaring.
### Misollar
```js
possibleBonus(3, 7) ➞ true

possibleBonus(1, 9) ➞ false

possibleBonus(5, 3) ➞ false
```
### Eslatmalar
- Siz orqaga harakat qila olmaysiz (shuning uchun №3 misol ishlamaydi).
- Agar siz allaqachon bir xil plitka ustida bo'lsangiz, ``false`` ni qaytaring, chunki siz oldinga siljiysiz.
- Faqat musbat butun son kiritilishini kuting
---

# [5. Right Shift by Division](https://edabit.com/challenge/ALGbgMWLuEdrh22fB)
## The right shift operation is similar to **floor division by powers of two.**
### Sample calculation using the right shift operator ( ``>>`` ):
```js
80 >> 3 = floor(80/2^3) = floor(80/8) = 10
-24 >> 2 = floor(-24/2^2) = floor(-24/4) = -6
-5 >> 1 = floor(-5/2^1) = floor(-5/2) = -3
```

### Write a function that **mimics** (without the use of >>) the right shift operator and returns the result from the two given integers.

### Examples
```js
shiftToRight(80, 3) ➞ 10

shiftToRight(-24, 2) ➞ -6

shiftToRight(-5, 1) ➞ -3

shiftToRight(4666, 6) ➞ 72

shiftToRight(3777, 6) ➞ 59

shiftToRight(-512, 10) ➞ -1
```
### Notes
- There will be no negative values for the second parameter ``y``.
- This challenge is more like recreating of the right shift operation, thus, **the use of the operator directly is prohibited.**
- Alternatively, you can solve this challenge via recursion.
- A **recursive** version of this challenge can be found via this [link](https://edabit.com/challenge/CtxRSuGhry3XK7wjh).
### Resources
- [Math.floor()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor)
- [Math.pow()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/pow)
- [Bitwise Operators](https://www.w3schools.com/js/js_bitwise.asp)

#### *Tarjima*
# 5. Bo'lim bo'yicha o'ngga siljish
## To'g'ri **siljish jarayoni ikki kuch bilan qavat bo'linishiga** o'xshaydi
### To'g'ri siljish operatori ( ``>>`` ) yordamida hisoblash namunasi:
```js
80 >> 3 = floor(80/2^3) = floor(80/8) = 10
-24 >> 2 = floor(-24/2^2) = floor(-24/4) = -6
-5 >> 1 = floor(-5/2^1) = floor(-5/2) = -3
```
### O'ngga siljish operatorini taqlid qiladigan (>> dan foydalanmasdan) va berilgan ikkita butun sondan natijani qaytaradigan funksiya yozing.

### Misollar
```js
shiftToRight(80, 3) ➞ 10

shiftToRight(-24, 2) ➞ -6

shiftToRight(-5, 1) ➞ -3

shiftToRight(4666, 6) ➞ 72

shiftToRight(3777, 6) ➞ 59

shiftToRight(-512, 10) ➞ -1
```
### Eslatmalar
- Ikkinchi parametr ``y`` uchun manfiy qiymatlar bo'lmaydi
- Bu qiyinchilik ko'proq to'g'ri siljish ishini qayta yaratishga o'xshaydi, shuning uchun operatordan to'g'ridan-to'g'ri foydalanish taqiqlanadi
- Shu bilan bir qatorda, bu muammoni rekursiya orqali hal qilishingiz mumkin
- Ushbu chaqiruvning rekursiv versiyasini ushbu [havola](https://edabit.com/challenge/CtxRSuGhry3XK7wjh) orqali topish mumkin
---


# 6  Perimeters with a Catch

Write a function that takes a number and returns the perimeter of either a circle or a square. The input will be in the form (letter `l`, number `num`) where the letter will be either `"s" `for square, or `"c" `for circle, and the number will be the side of the square or the radius of the circle.

Use the following formulas:
```js
Perimeter of a square: 4 * side.
Perimeter of a circle: 6.28 * radius.
```
The catch is you can only use `arithmetic `or `comparison operators`, which means:

- No if... else statements.
- No objects.
- No arrays.
- No formatting methods, etc.
- The goal is to write a short, [branch-free ](https://en.wikipedia.org/wiki/Branch_(computer_science)#Branch-free_code)piece of code.

**Examples**
```js
perimeter("s", 7) ➞ 28

perimeter("c", 4) ➞ 25.12

perimeter("c", 9) ➞ 56.52
```
**Notes**
No rounding is needed.


## tarjima 

# 6. Perimeters with a Catch
#### ``#conditions #geometry #logic #math #numbers``
### Write a function that takes a number and returns the perimeter of either a circle or a square. The input will be in the form (letter ``1``, number ``num``) where the letter will be either ``"s"`` for *square*, or ``"c"`` for *circle*, and the number will be the side of the square or the radius of the circle.

Quyidagi formulalardan foydalaning:

```js
Perimeter of a square: 4 * side.
Perimeter of a circle: 6.28 * radius.
```

Gap shundaki, siz faqat `arifmetik` yoki `taqqoslash operatorlari` dan foydalanishingiz mumkin, ya'ni:

- Yo'q, agar ... boshqa bayonotlar.
- Hech narsa yo'q.
- Massivlar yo'q.
- Formatlash usullari yo'q va hokazo.
- Maqsad qisqa, [filialsiz] yozish kod qismi.

**Misolar**

```js
perimeter("s", 7) ➞ 28

perimeter("c", 4) ➞ 25.12

perimeter("c", 9) ➞ 56.52
```
**eslatma**

Yaxlitlash kerak emas.


# 7 Find Number of Digits in Number**

Create a function that will return an integer number corresponding to the amount of digits in the given integer` num`.

**Examples**

```js
num_of_digits(1000) ➞ 4

num_of_digits(12) ➞ 2

num_of_digits(1305981031) ➞ 10

num_of_digits(0) ➞ 1
```
**Notes**

    Try to solve this challenge without using strings!


## Tarjima

# 7 Raqamdagi raqamlar sonini toping

Berilgan tamsayı` num`dagi raqamlar miqdoriga mos butun sonni qaytaradigan funksiya yarating.

**Misollar**

```js
num_of_digits(1000) ➞ 4

num_of_digits(12) ➞ 2

num_of_digits(1305981031) ➞ 10

num_of_digits(0) ➞ 1
```
**eslatma**

   Ushbu muammoni simlardan foydalanmasdan hal qilishga harakat qiling!
/////////////////////////////////////////////////////////////////////////////////
  # 8 Burglary Series (04): Add its Name

Given three arguments ⁠— an object `obj` of the stolen items, the pets `name` and a `value `⁠— return an object with that name and value in it (as key-value pairs).

**Examples**
```js
addName({}, "Brutus", 300) ➞ { Brutus: 300 }

addName({ piano: 500 }, "Brutus", 400) ➞ { piano: 500, Brutus: 400 }

addName({ piano: 500, stereo: 300 }, "Caligula", 440) ➞ { piano: 500, stereo: 300, Caligula: 440 }
```
**Notes**

The value argument will be a number.

# tarjimasi


# 8 O'g'rilik seriyasi (04): Uning nomini qo'shing

Uchta argumentni hisobga olgan holda - o'g'irlangan narsalarning "obj" ob'ekti, uy hayvonlari "nomi" va "qiymat" - bu nom va undagi qiymatga ega ob'ektni qaytaradi (kalit-qiymat juftlari sifatida).

**Misollar**
```js
addName({}, "Brutus", 300) ➞ { Brutus: 300 }

addName({ piano: 500 }, "Brutus", 400) ➞ { piano: 500, Brutus: 400 }

addName({ piano: 500, stereo: 300 }, "Caligula", 440) ➞ { piano: 500, stereo: 300, Caligula: 440 }
```
**Eslatma**

Qiymat argumenti raqam bo'ladi.

////////////////////////////////////////////////////////////////////

# 9 Derivative of a Function

Create a function that takes numbers `b `and `m` as arguments and returns the derivative of the function `f(x)=x^b` with respect to `x `evaluated at `x=m,` where `b` and `m `are constants.

**Examples**
```js
derivative(1, 4) ➞ 1

derivative(3, -2) ➞ 12

derivative(4, -3) ➞ -108
```
**Notes**

`^ `in the context of this challenge means "to the power of", also known as the "exponent" operator.

# 9 Funktsiyaning hosilasi


Argument sifatida `b`va `m` raqamlarini oladigan va `x=m`da baholangan `x`ga nisbatan `f(x)=x^b` funksiyaning hosilasini qaytaradigan funksiya yarating, bunda `b` va `m ` doimiylardir.

**Misollar**
```js
derivative(1, 4) ➞ 1

derivative(3, -2) ➞ 12

derivative(4, -3) ➞ -108
```
**Eslatma**

`^ `bu chaqiriq kontekstida "kuchga" degan ma'noni anglatadi, shuningdek, "ko'rsatkich" operatori sifatida ham tanilgan.

//////////////////////////////////////////////////

# 10 Which Generation Are You?

Try finding your ancestors and offspring with code.

Create a function that takes a number `x `and a character `y `(`"m" `for male, `"f"` for female), and returns the `name of an ancestor (m/f) or descendant (m/f).`

- If the number is negative, return the related ancestor.
- If positive, return the related descendant.
- You are generation `0`. In the case of` 0 `(male or female), return `"me!"`.

**Examples**
```js
generation(2, "f") ➞ "granddaughter"

generation(-3, "m") ➞ "great grandfather"

generation(1, "f") ➞ "daughter"
```
**Notes**

Check the `Resources` tab for helpful hints.

```js 
Generation	 Male	                Female

-3	         great grandfather	    great grandmother
-2	         grandfather	        grandmother
-1	         father	                mother
 0	         me!	                me!
 1	         son	                daughter
 2	         grandson       	    granddaughter
 3         	 great grandson	        great granddaughter
```

# 10 Sizning avlodingiz qaysilar?

Kod yordamida ota-bobolaringiz va avlodlaringizni topishga harakat qiling.