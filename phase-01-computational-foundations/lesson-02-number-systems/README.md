# Lesson 2 - Number Systems: Why Binary Exists

## Objective

To understand what a number system is, how different bases work, and why computers use the binary system to represent data.

---

## Reflection

### What is a number system?

A number system is an agreed-upon method of representing numbers using a specific set of digits and a base. The base determines how place values are calculated and how numbers are represented. Common examples include base 2 (binary), base 10 (decimal), and base 16 (hexadecimal).

---

### What is the difference between decimal and binary?

Decimal is a base-10 number system that uses the digits 0-9. Each place value is ten times greater than the place value immediately to its right (ones, tens, hundreds, thousands, etc.). It is the number system humans use in everyday life.

Binary is a base-2 number system that uses only the digits 0 and 1. Each place value is two times greater than the place value immediately to its right (ones, twos, fours, eights, etc.). It is the primary number system used by computers to represent data.

---

### Why do computers use binary?

Computers use binary because their electronic circuits operate using two stable electrical states, which can be represented as ON and OFF. These two states naturally correspond to the binary digits 1 and 0, making binary a simple, reliable, and efficient way for computers to process and store information.

---

### What is a bit?

A **bit** (binary digit) is the smallest unit of information in computing. A bit can have only one of two possible values: **0** or **1**.

---

### What is a byte?

A **byte** is a group of **8 bits**.

Example:

```
11111111
```

---

### What is a nibble (nybble)?

A **nibble** (also spelled **nybble**) is a group of **4 bits**.

Example:

```
1010
```

---

## Exercises

### Decimal to Binary

| Decimal | Binary |
|--------:|:-------|
|5 | 101<sub><sub>2</sub></sub>|
|9 | 1001<sub><sub>2</sub></sub>|
|13 | 1101<sub><sub>2</sub></sub>|
|21 | 10101<sub><sub>2</sub></sub>|
|32 | 100000<sub><sub>2</sub></sub>|

---
### Binary to Decimal

| Binary | Decimal |
|--------:|:-------|
| 101<sub><sub>2</sub></sub>| 5 |
| 1001<sub><sub>2</sub></sub>| 12 |
| 1101<sub><sub>2</sub></sub>| 17 |
| 10101<sub><sub>2</sub></sub>| 31 |
| 100000<sub><sub>2</sub></sub>| 32 |

---

## What I learned

This lesson taught me that there are many number systems besides binary, decimal, and hexadecimal. Any positive integer greater than one can be used as the base of a number system, such as base 3, base 5, or even base 60.

I also learnt that the base determines the place value within a number system. For example:

- Base 10 uses place values of 1, 10, 100, 1000...
- Base 2 uses place values of 1, 2, 4, 8, 16...
- Base 16 uses place values of 1, 16, 256, 4096...

For fractional values, each place after the decimal point represents the reciprocal of the base raised to increasing powers.

Examples:

**Base 2**

```
1/2, 1/4, 1/8, 1/16...
```

**Base 16**

```
1/16, 1/256, 1/4096...
```

I also learnt that we can distinguish number systems by writing the base as the subscript.

Examples:

```
101₁₀
101₂
101₁₆
```

Although the digits appear the same, they represent completely different values depending on the base.

Another important realization was that hexadecimal is used in RGB color codes. As a developer, I have used hexadecimal colors many times, but I have never stopped to think why hexadecimal was chosen or that it was a practical application of the base-16 number system.

Finally, I learned that binary numbers should be read digit by digit (for example, "one-zero-one") rather than as decimal numbers ("one hundred and one"). This helps avoid confusion between different number systems.

---

## Pattern Discovery

The most important pattern I discovered is that changing the base changes the place values, but the positional number system itself remains exactly the same.

Every number system follows the same principle:

- Each position represents a power of the base.
- The only thing that changes is the value of the base.

---

## Engineering Reflection

Initially, I thought decimal was more convenient simply because powers of ten are easy to recognize by counting zeros. Through this lesson, I realized that the real advantage comes from familiarity and the structure of the positional number system.

I also connected binary to computer hardware. Since computers rely on electronic circuits that operate using two stable electrical states (ON and OFF), binary provides a natural way to represent information electronically.

This made me realize that mathematics and computer hardware are deeply connected.

---

## Discovery Question

**Question**

If computers only understand ON and OFF, how can they represent letters, pictures, music, and videos?

**My Current Hypothesis**

I think computers use different encoding systems to represent different kinds of information. For example, colors can be represented using hexadecimal values that are ultimately converted into binary. I don't know yet how text, images, music and videos are represented internally, but I'm excited to learn how everything eventually becomes binary.

---

## Challenges

This lesson was challenging because it introduced several unfamiliar number systems and different place values. However, by practicing conversions between decimal and binary and recognizing the underlying patterns, I became much more comfortable with the concepts.

---

## Key Takeaways

- A number system is defined by its base.
- The base determines the place values used to represent numbers.
- Binary uses only 0 and 1 because computers operate using two stable electrical states.
- A bit is a single binary digit, while a byte consists of 8 bits.
- The same positional notation applies to every number system.
- Hexadecimal has practical applications in computing, including RGB color representation.
- Understanding the logic behind number systems is more valuable than memorizing conversion rules.

---

## Looking Ahead

This lesson showed me that number systems are the bridge between mathematics and computer science. I am looking forward to learning how computers use binary to represent memory, characters, images, audio, video, and eventually entire software systems!!!