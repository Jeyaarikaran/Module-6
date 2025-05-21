# 🐍 Python OOP:Polymorphism with Circle and Square Classes Using perimeter() and area() Methods 

## 🎯 AIM :
To demonstrate polymorphism by defining perimeter() and area() methods in both Circle and Square classes and invoke them to compute and display respective geometric values.

## 🧠 ALGORITHM :
1.Import the math module for mathematical constants and functions.

2.Define a class Square with an instance variable side.

3.Implement perimeter() to calculate the perimeter of the square as 4 * side.

4.Implement area() to calculate the area of the square as side * side.

5.Define a class Circle with an instance variable radius.

6.Implement perimeter() to calculate the circumference as 2 * pi * radius.

7.Implement area() to calculate the area as pi * radius^2.

8.Take input values for the side of the square and the radius of the circle.

9.Create objects of Square and Circle using input values.

10.Call and print the results of perimeter() and area() methods for both objects.





## 💻 Program :
```.py
import math
class calculation:
    def __init__(self,a,b):
        self.a=a
        self.b=b
class Area(calculation):
    def perimeter(self):
        print(f"Perimeter computed for square:  {4*self.a}")
    def area(self):
        print(f"Area computed for square:  {self.a**2}")
class Circle(calculation):
    def perimeter(self):
        print(f"Perimeter computed for Circle:  {2*math.pi*self.b}")
    def area(self):
        print(f"Area computed for Circle:  {math.pi*self.b*self.b}")
a=int(input())
b=int(input())
sqr=Area(a,b)
cir=Circle(a,b)
for i in (sqr,cir):
    i.perimeter()
    i.area()
```

## Output :

![image](https://github.com/user-attachments/assets/ec84f2fd-7d2a-49d6-b587-b0f2a4569fa3)


## Result :
The program successfully uses polymorphism to call the same method names (perimeter() and area()) on different classes (Circle and Square), calculating and displaying correct geometric values based on the shape.

