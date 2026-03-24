# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
~~~
a = int(input("Enter an integer for the real part: "))
b = int(input("Enter an integer for the imaginary part: "))
x = complex(a, b)
print("\nThe complex number is:", x)
print("Real Part:", x.real)
print("Imaginary Part:", x.imag)
~~~

## Output
Enter an integer for the real part: 3 Enter an integer for the imaginary part: 5

The complex number is: (3+5j) Real Part: 3.0 Imaginary Part: 5.0

## Result
The program successfully reads two integers, constructs a complex number using the complex() constructor, and retrieves its components using the .real and .imag attributes.
