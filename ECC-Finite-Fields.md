## Introduction To The Mathematics for Cryptography


### Finite Fields & Modular Arithmetic 

Intuitively a Finite Field aslo named Galois Field (For Evariste Galois)  is a set of numbers usually ordered that respects a set of axioms :

- F is a finite field ==> (+,-, * , / ) are closed under F ( meaning that if we take a & b from F ) a + b is inside F same for the other ops .
- The Most Referenced Field is the Integers mod P fields where P is a Prime :exclamation:

**Prime Fields** : 
F <sub>p</sub> : is a Prime Field defined as the set of integers from 0 to P-1

*Examples*: F<sub>23</sub> { 0,1,2...,22 } , F<sub>223</sub> {0,1,2...,222} and so on .

The Operations Under a Prime Field are leveraged using modular arithmetic a/k/a clock-math :

**Remainder Math** 22 % 5 = 4 R 1 | 23 % 3 = 6 R 5

**Operations under prime fields** : 

Let's fix F<sub>23</sub> :

- *Add* : 11 + 9 = 20 % 23 = 3 || 22 + 8 = 30 % 23 = 7 
    - In general adding two numbers under a prime field is equal to the ( a+b mod p )
- *Sub* : 11 - 17 = -6 % 23 =  17 
    - Same Principle as Addition 

- *Mul* : 2 * 4 = 8 % 23 = 8 || 15 * 3 = 45 % 23

- *Pow* : 11<sup>3</sup> = 1331 % 23 = 20
