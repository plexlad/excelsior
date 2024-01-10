## Day 1:
1. Convert from binary to decimal
2. Convert from decimal to binary

Essentially, you are on an island. You have a box of transistors. What do you do?

1. Functions (Inputs and Outputs)
2. Memory (How do we store stuff?)
3. State Machines

In a binary number, each character is known as a bit. The right most bit is known as the *least-significant bit (LSB)*. The left most bit is referred to as the *most-significant bit (MSB)*. Each is respectively the biggest and smallest bit. A group of 8 bits is called a byte.
# Binary to decimal
1011 from binary to decimal.


| $2^3$ | $2^2$ | $2^1$ | $2^0$ |  |
| ---- | ---- | ---- | ---- | ---- |
| 8 | 4 | 2 | 1 |  |
| 1 | 0 | 1 | 1 |  |
| 8 | 0 | 2 | 1 | = 11 |


> Left shift (adding a 0 to the right of the bits in binary).
> This doubles the number!

# Decimal to Binary
Binary to decimal places
$...64, 32, 16, 8, 4, 2, 1$

37 to binary.
Get the floor of the number divided by two and repeat this process. If it is odd, that is a bit.

The "floor" function rounds the number down to the nearest "ones" place.

37 is odd so we have 1.
floor(37/2) is 18, which is even. That gives us 01.
floor(18/2) is 9, which is odd. That gives us 101.
floor(9/2) is 4, which is even. That gives us 0101.
floor(4/2) is 2, which is even. That gives us 00101.
floor(2/1) is 1, which is odd. That gives us 100101.