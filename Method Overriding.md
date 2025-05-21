# 🐟 Method Overriding-Perform addition of two complex number using binary '+' operator overloading

## 🧠 AIM:
To implement operator overloading in Python to perform addition of two complex numbers using the binary + operator.



## 📋 ALGORITHM:
1.Define a class named complex.

2.Initialize the real and imaginary parts in the constructor (__init__ method).

3.Overload the + operator by defining the __add__ method to add corresponding real and imaginary parts.

4.Define the __str__ method to return the complex number in (real, imag) format.

5.Create two objects of the complex class with given values.

6.Use the + operator to add the two complex objects.

7.Print the result.


## 💻 PROGRAM:
```.py
class complex:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def __sub__(self,other):
        return self.a+other.a,self.b+other.b
Ob1 = complex(1, 2)
Ob2 = complex(2, 3)
print(Ob1-Ob2)
```

## OUTPUT :
![image](https://github.com/user-attachments/assets/ca9087eb-4f51-4089-8a27-2bd9e04af7a2)

## RESULT :
The program correctly overloads the + operator to add two complex numbers and displays the result in the desired format.
