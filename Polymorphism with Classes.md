# # 🐍 Python OOP: Polymorphism Demonstration Using diet() Method in Lion and Giraffe Classes

## 🎯 AIM :
To demonstrate polymorphism by creating two classes, Lion and Giraffe, each having a diet() method with different implementations and displaying respective dietary habits.



## 🧠 ALGORITHM :
1.Define a class Lion with a method diet() that prints "carnivore".

2.Define a class Giraffe with a method diet() that prints "herbivore".

3.Create an object of the Lion class and call its diet() method.

4.Create an object of the Giraffe class and call its diet() method.

5.Observe that each object calls its own class's diet() method independently.


## 💻 Program :
```.py
class Lion:
    def diet(self):
        print("carnivore")
class Giraffe:
    def diet(self):
        print("herbivore")
  

obj_lion=Lion()
obj_giraffe=Giraffe()

obj_lion.diet()
obj_giraffe.diet()
```

## Output:


![image](https://github.com/user-attachments/assets/3e5ba922-e43c-4854-b501-504ed823bbcb)


## Result :
The program successfully illustrates polymorphism where the same method name diet() behaves differently depending on the class of the object calling it. Objects of Lion and Giraffe invoke their respective methods showing distinct behaviors.


