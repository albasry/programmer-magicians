# Programmer Magicians, Conjuring Math for Code Wizards!

---

[toc]

---

# Introduction

Mathematics is the language of *patterns*, *shapes*, *quantities*, and *relationships*. It's a discipline that underpins the fabric of our universe, guiding everything from the precise calculations behind technological advancements to the elegant symmetries found in nature. At its core, math explores the logic and structure of numbers, space, and change, offering tools to solve problems, make predictions, and understand the world around us. From arithmetic to calculus, from geometry to abstract algebra, mathematics serves as a fundamental tool for understanding, interpreting, and navigating our complex reality.

Mathematics serves as the foundational bedrock upon which the towering edifice of programming stands. Much like a well-crafted symphony, programming intricately weaves mathematical concepts into its very fabric. From the algorithms that power search engines to the sophisticated code running complex simulations, mathematics is the silent conductor orchestrating the symphony of code.

For programmers, mathematics isn't just a theoretical construct; it's a pragmatic necessity. Concepts from discrete mathematics, such as logic, sets, and graph theory, form the backbone of algorithm design and data structures. Understanding probability and statistics enables programmers to build robust systems that make informed decisions and handle uncertainties gracefully. Calculus and linear algebra find applications in fields like graphics programming, where they help create stunning visual effects and simulations.

Furthermore, mathematics cultivates a mindset of logical reasoning and problem-solving, essential traits for programmers tackling intricate challenges. It provides a framework for breaking down complex problems into manageable components and devising elegant solutions. A solid grasp of mathematical principles empowers programmers to write efficient, optimized code that drives innovation and efficiency in the technological landscape.

In essence, the symbiotic relationship between mathematics and programming underscores the indispensable role of mathematical proficiency in the toolkit of every programmer, enabling them to craft elegant, efficient, and groundbreaking solutions.

---

# Numeral System

:::success
:bulb: **The Simple Art of Numbers**

Understanding the foundational aspects of numbers can be incredibly beneficial for programmers without necessarily diving into the complexities. 
:::

The numeral system is a method or system used to represent numbers in a symbolic form. It encompasses a set of symbols or characters along with rules and conventions for their arrangement to denote numerical values. This system provides a way to express quantities, perform mathematical operations, and communicate numeric information.

Numeral systems can vary based on cultural, historical, or practical considerations. They differ in the symbols used, the base or radix (the number of unique symbols used in the system), and the positional value each symbol holds within a number.

---
## Types of Numeral System

:::info
:pushpin: **Human Legacy**

The history of numeral systems spans thousands of years and involves various civilizations. Early humans used tally marks simple notches on sticks or stones to count and keep track of quantities. These evolved into more sophisticated counting systems in ancient civilizations. Starting from the Sumerian civilization in Mesopotamia (modern-day Iraq) to Modern Era.
:::

:::success
:bulb: **Numbers Base**

Number bases refer to the system used to represent numbers. In a base-N system, where N represents the base, each digit's position from right to left represents an increasing power of N.
:::

### The Unary System

* The system's simplicity makes it easy to comprehend and apply, especially in rudimentary counting methods. Historically, early human civilizations used unary methods, such as tally marks or notches, to count or keep track of items due to their straightforward nature and ease of use.

* The unary system is a numerical representation method that utilizes a single symbol to represent all values.

* In the unary system, typically represented as '|', each occurrence of the symbol corresponds to the value of '|'. To represent a specific number, the symbol is repeated a certain number of times. For example, in unary, the number '3' would be depicted as '|||'—three instances of the symbol '|' representing the quantity.

* While the unary system holds theoretical significance in fields like computational theory and mathematics, it is impractical for large-scale calculations due to its inefficiency in representing larger numbers. Nonetheless, its simplicity and foundational role in understanding fundamental concepts make it valuable in theoretical discussions and educational contexts.

![The Unary System](https://hackmd.io/_uploads/H1xIz1sPT.jpg 'The Unary System')

---
### The Decimal System

* The decimal system, also known as the base-10 numeral system, is a numerical notation system that uses ten unique symbols to represent numeric values. It is the most commonly used numeral system worldwide and serves as the foundation for everyday arithmetic, mathematics, science, finance, and various other fields.

* **Positional Notation :** The value of a digit in a decimal number is determined by its position or place value in relation to the decimal point. Moving left from the decimal point increases the magnitude by powers of ten (10, 100, 1000, and so on), while moving right decreases it by fractions of ten (0.1, 0.01, 0.001, and so forth).
    * For example:
        * In the number 425.63, the '4' represents 400 (10^2^), the '2' represents 20 (10^1^), the '5' represents 5 (10^0^), the '6' represents 6 tenths (10^-1^), and the '3' represents 3 hundredths (10^-2^).

![The Decimal System](https://hackmd.io/_uploads/HyaSXb9D6.jpg 'The Decimal System')

---
![Decimal Number](https://hackmd.io/_uploads/rJi6cHjDa.jpg 'Decimal Number')

---

### The Binary System

* The binary system is a numerical notation system that uses only two distinct symbols, typically represented as 0 and 1, to express numeric values. The binary system is based on a base-2 notation, relying solely on the two symbols, 0 and 1.
    * **Base-2 Notation :** The term "binary" stems from the Latin word "binarius," meaning "consisting of two." In this system, each digit's value represents a power of two, with the rightmost digit signifying units, the next representing twos, then fours, eights, and so on, doubling with each position.
    * **Digital Representation :** Binary digits, commonly referred to as bits, are the fundamental units of information in digital systems. Computers use binary code to store, process, and transmit data. 'One' denotes electricity, while 'zero' denotes its absence. Groups of eight bits form a byte, allowing for the representation of larger values and a wider range of data types.
        * For example :
            The binary number '1010' signifies 1 eight (2^3^), 0 fours, 1 two (2^1^), and 0 units, equating to the decimal value of 10.

![The Binary System](https://hackmd.io/_uploads/Hy6pxIoDp.jpg 'The Binary System')

---
![Convert binary to decimal](https://hackmd.io/_uploads/HyYGPUjwT.jpg 'Convert binary to decimal')

---

#### **Parts of Byte**
* A crumb is a 2 Bit
* A nibble is a 4 Bit

---
![Parts of Byte](https://hackmd.io/_uploads/S1Kquonv6.jpg 'Parts of Byte')

---

:::info
:pushpin: **Higher parts of a byte**

Unsigned binary numbers are, by definition, positive numbers and thus do not require an arithmetic sign. An m-bit unsigned number represents all numbers in the range 0 to 2m - 1. For example, the range of 8-bit unsigned binary numbers is from 0 to 25510 in decimal and from 00 to FF16 in hexadecimal.`
* A QWORD is a 64-bit unsigned integer.
* A DWORD is a 32-bit unsigned integer (range: 0 through 4294967295 decimal). Because a DWORD is unsigned, its first bit (Most Significant Bit (MSB)) is not reserved for signing.
* A WORD is a 16-bit unsigned integer (range: 0 through 65535 decimal). Because a WORD is unsigned, its first bit (Most Significant Bit (MSB)) is not reserved for signing.
* A Byte is a 8-bit unsigned integer.
:::

---

### The Hexadecimal System

* The hexadecimal system provides a human-friendly notation.
* The hexadecimal system is a numerical notation system used in mathematics and computing that operates on a base-16 representation.
    * **Base-16 Notation :** The term "hexadecimal" derives from the Greek words "hexa" (six) and "deca" (ten). In this system, each digit's value represents a power of sixteen. After reaching 9, the system continues with the letters A-F, where 'A' signifies 10, 'B' stands for 11, and so on up to 'F' representing 15.
    * **Compact Representation :** Hexadecimal provides a concise way to represent large binary values. Each hexadecimal digit corresponds to four binary digits (bits), simplifying the representation of binary data in computer systems.
        * For example:
            The hexadecimal number '1F' signifies 1 sixteen (16^1^) and 15 units (16^0^), equating to the decimal value of 31.

---
![Hexadecimal System](https://hackmd.io/_uploads/HJ170IsP6.jpg 'Hexadecimal System')

---
![Convert Dec to Hexa](https://hackmd.io/_uploads/HJ_z4q3va.jpg 'Convert Dec to Hexa')

---
![Convert Hexa to Dec](https://hackmd.io/_uploads/SJeoN9nP6.jpg 'Convert Hexa to Dec')

---
![Convert Hexa to Deca](https://hackmd.io/_uploads/SJ_gB9hDT.jpg 'Convert Hexa to Deca')

---
![Convert hexa to binary](https://hackmd.io/_uploads/rybtlhnv6.jpg 'Convert hexa to binary')

---
![00_convert_binary_hexa](https://hackmd.io/_uploads/HysnQ2hDT.jpg)

---

#### **Hexadecimal Prefixes**

*In various programming languages and systems, different prefixes are used to represent hexadecimal numbers:*

> **Assembly Language:** The prefix can vary depending on the specific assembly language syntax. For instance, in x86 assembly, hexadecimal numbers might not have a specific prefix; they are recognized by the 0-9 and A-F characters.

|Language|Prefix|Example|
|-----|:-----:|:-----:|
|Unicode|U+|U+2F3A|
|C, C++, Java, Prel, Python|0x|0x2FC|
|HTML,CSS|#|#FFFFFF|
|XML|&#|&#4C7|

---

### The Octal System

* The octal system is a numerical notation system based on a base-8 representation, utilizing eight unique symbols—0 to 7—to express numeric values.

:::warning
:bell:  **History of the octal system**

When computers and programming were in their early stages, octal (base-8) was a commonly used numeral system, particularly in computer systems that processed data in multiples of 3 bits.
Each octal digit represents 3 bits. For example:

- 1 octal digit = 3 bits
- 2 octal digits = 6 bits

However, a full byte, which consists of 8 bits, doesn't align neatly with the octal system. It's more common to see octal representation used for groups of bits that are multiples of 3 (like 6 or 12 bits) rather than a full byte (8 bits).
:::

* **Base-8 Notation :** The term "octal" originates from the Latin word "octo," meaning eight. Each digit's value in the octal system represents a power of eight. For instance, in the octal number '72', the '7' denotes 7 eights (8^1), and the '2' represents 2 units (8^0), totaling 58 in the decimal system.
* **Representation and Place Value :** Similar to other positional numeral systems, the position of each digit in an octal number determines its significance. Moving left from the rightmost digit, each position corresponds to a higher power of eight.

#### **Octal System Prefixe**
> The prefix of octal system is "0o"
- 0o72
- 0o51

---
![Octal System](https://hackmd.io/_uploads/r1dzUc6Da.jpg 'Octal System')

---
![Convert deca to octal](https://hackmd.io/_uploads/ryin6yRw6.jpg 'Convert deca to octal')

---
![Convert octal to decimal](https://hackmd.io/_uploads/r1wyCJ0wa.jpg 'Convert octal to decimal')

---
![Convert octal to decimal](https://hackmd.io/_uploads/H16VmlCDa.jpg 'Convert octal to decimal')

---

## The integers
* An integer is any number from a set of whole numbers and their inverse, the numbers with the same absolute value but an opposite sign. `-3, -2, -1, 0, 1, 2, 3`
* **The absolute value** The absolute value of a number is that same number, but without the sign in front of it.  The absolute value actually shows us what the distance is from that number to 0 on the number line.

---
![The absolute value](https://hackmd.io/_uploads/HkCK2lCDT.jpg 'The absolute value')

---
## The fractions
* A fraction is a mathematical quantity that is not a whole number.

> 1/2, 1/4, 2/6.

---
![The fractions](https://hackmd.io/_uploads/Syw5WhB_a.jpg 'The fractions')

---
* Even though fractions might not be equal to one whole, fractions do tell you how many parts of a whole you have. For example, if you have 3 pieces left of an 8-slice pizza, you have 3/8 of the pizza.

:::info
:bell:  **Clarification**

The difference between  1/2 and 0.5 lies in their representation.

- 1/2 is a fraction, representing one part of a whole divided into two equal parts. It's a way to express a portion or ratio.
- 0.5 is a decimal number, specifically the numerical representation of the fraction 1/2. It represents the same value as 1/2, just in a different form.
:::

---
# Characters and Symbols
Characters and symbols are represented using binary. Because machines understand zeros and ones and nothing else. Each character is allocated a unique binary pattern, enabling computers to process textual information.There are many encoding schemes used for this purpose, such as ASCII and Unicode.

## ASCII, American Standard Code for Information Interchange.

Originally developed for telegraphs, ASCII uses a 7-bit binary code to represent text characters. This encoding scheme allows computers to understand and exchange textual information by using a standardized set of characters.

---
![ASCII Code](https://hackmd.io/_uploads/ByVd11LOp.jpg 'ASCII Code')

---
**ASCII Table:** [ASCII Table](https://theasciicode.com.ar/ 'ASCII table link')

---

## Unicode
Unicode is a more extensive character encoding standard that uses a variable number of bits (typically 8, 16, or 32 bits) to represent characters from different languages and scripts. It supports a much larger number of characters and symbols from various writing systems worldwide.

---
![Unicode](https://hackmd.io/_uploads/B19hxJLOT.jpg 'Unicode')

---
**Unicode Table:** [Unicode Table](https://www.unicode.org/charts/ 'Unicode table link')

---

[toc]


---
# Arithmetic 
:::info
:dart:  **First Steps**

Arithmetics, often regarded as the language of the universe, relies on fundamental operations as its building blocks. These basic operations: addition, subtraction, multiplication, and division, form the foundation upon which complex mathematical concepts are built. They are essential in solving problems across various domains, from basic arithmetic to advanced calculus and beyond.
:::

---
## Fundamental Operations
:::danger
:mega: **To remember**

"As a programmer, mastery isn't about memorizing the multiplication table; it's about understanding and executing multiplication."

[@ibrahimalbasri](https://hackmd.io/@ibrahimalbasri)
:::
### The Four Fundamental Operators

1. **Addition** "+"
    * `One Add One Equals Two`, 1 + 1 = 2
    * Adding Integers
    * Adding fractions
2. **Subtraction** "-"
    * `One Subtract One Equals Zero`, 1 - 1 = 0
    * Subtracting Integers
    * Subtracting fractions

3. **Multiplication** "×, *"
    * `Three Multiply Three Equals Nine`, 3 × 3 = 9
    * Multiplying Integers
        * *Rules of multiplication*
        * If two positive or two negative numbers are multiplied, their product is a positive number.
            * ( + × + = + )
            * ( - × - = + )
        * If two numbers of different signs are multiplied, their product is a negative number.
            * ( + × - = - )
            * ( - × + = - )

    * Multiplying fractions

4. **Division** "÷, ̶̶̶ , /"
    * `Three Divide Three Equals One`, 3 ÷ 3 = 1
    * Dividing Integers
        * *Rules of division*
        * If two positive or two negative numbers are divided, their quotient is a positive number.
            * ( + ÷ + = + )
            * ( - ÷ - = + )
        * If two numbers of different signs are divided, their quotient is a negative number.
            * ( + ÷ - = - )
            * ( - ÷ + = - )

    * Dividing fractions

---
## Secondary Operations
### Exponents and Radicals (Roots)
Besides the fundamental four operations, there exist two more operators: Exponents and Radicals.

1. **Exponents**
    * Exponent Sign "xⁿ", "x²", "x^2^"
    * The exponent is refers to how many times a number is multiplied by itself.
    * `Three Exponent Two Equals Nine`, 3² = 9, Because 3 × 3 = 9
    * `Three Exponent Three Equals Twenty Seven`, 3³ = 27, Because 3 × 3 × 3 = 27
2. **Radicals**
    1. *Square Root*
        * Square Root Sign √x
        * The square root is an operator of a number that, when multiplied by itself, gives the original number.
        * `Square Root of Nine Equals Three`, √9 = 3, Because 3 × 3 = 9
    2. *Cube Root*
        * Cube Root Sign ³√x
        * `Cube Root of Eight Equals Two`, ³√8 = 2, Because 2 × 2 × 2 = 8

---

### The percentage

---
## Logic & Comparing Numbers

1. **Equals**
    * Equals-to Sign "=", "=="
    * `One Equals-to Three It's False`, 1 == 3 : False
2. **Not equals**
    * Not-equals-to Sign "≠", "!="
    * `One Not-equals-to Three It's True`, 1 != 3 : True
3. **Less-than**
    * Less-than Sign "<"
    * `One Less-than Two It's True`, 1 < 2 : True
4. **Greater-than**
    * Greater-than Sign ">"
    * `One Greater-than Two It's False`, 1 > 2 : False
5. **Less-than or Equal**
    * Less-than or Equal Sign "≤", "<="
    * `One Less-than or Equal Four It's True`, 1 <= 4 : True
6. **Graeter-than or Equal**
    * Graeter-than or Equal Sign "≥", ">="
    * `One Graeter-than or Equal Four It's False`, 1 >= 4 : False

