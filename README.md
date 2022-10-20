# Mashqlar
Githubdagi daslabki kodlarim 
#sonning EKUBI, EKUKI va Factorialini topish dasturi in Python.
from math import gcd, lcm, factorial
a, b = int(input('a = ')), int(input('b = '))
print(f"{a} va {b} sonlarining EKUBI = {gcd(a,b)}")
print(f"{a} va {b} sonlarining EKUKI = {lcm(a, b)}")
print(f"{a} va {b} sonlarining factoriali:\n{a}! = {factorial(a)}\n{b}! = {factorial(b)}")
