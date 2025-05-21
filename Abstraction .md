# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM :
To implement an abstract class in Python using the abc module and demonstrate method overriding and instance checking with derived classes.

## 🧠 ALGORITHM :
   1.Import ABC and abstractmethod from abc.
   
   2.Create abstract class Absclass with:
   
   3.Abstract method task(self, value)
   
   4.Regular method print(self)
   
   5.Create two subclasses test_class and example_class:
   
   6.Both override the task() method.
   
   7.Create objects of both subclasses.
   
   8.Call task() on each object.
   
   9.Use isinstance() to verify inheritance.



## 💻 Program :
```.py
from abc import ABC, abstractmethod

class Absclass(ABC):
    def print(self, x):
        print("Passed value: ", x)

    @abstractmethod
    def task(self):
        pass

class test_class(Absclass):
    def task(self):
        print("We are inside test_class task")

class example_class(Absclass):
    def task(self):
        print("We are inside example_class task")

test_obj = test_class()


example_obj = example_class()


test_obj.task()
test_obj.print(100)

example_obj.task()
example_obj.print(200)

print("test_obj is instance of Absclass? ", isinstance(test_obj, Absclass))
print("example_obj is instance of Absclass? ", isinstance(example_obj, Absclass))
```

## Output :
![image](https://github.com/user-attachments/assets/0ecb331e-0d1a-4713-9458-e6b4a0e9c310)


## Result :
The program correctly demonstrates abstract class usage, method overriding, and confirms both objects are valid instances of the abstract base class.







