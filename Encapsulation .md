# 🐍 Python OOP: Employee class by defining employee attributes

## 🎯 AIM :
To create an Employee class in Python with attributes name and salary, and define instance methods show() to display employee details and work() to show assigned tasks.




## 🧠 ALGORITHM :
1. Define a class Employee.
 
2.Create an __init__() constructor to initialize name and salary.
   
3.Define a show() method to print name and salary.
   
4. Define a work(task) method to print the task being worked on.
   
5.Create an object of the Employee class with sample data.
   
6.Call the show() and work() methods on the object.



## 💻 Program :
```.py
   class Employee:
    def __init__(self, name, salary, project):
        self.name = name
        self.salary = salary
        self.project = project
    def show(self):
        print("Name: ", self.name, 'Salary:', self.salary)
        
    def work(self):
        print(self.name, 'is working on', self.project)

per1=Employee("Jessa",8000,"NLP")
per1.show()
per1.work()
```

## Output :
![image](https://github.com/user-attachments/assets/3b780d0a-630e-4740-849e-96482cc4143c)


## Result :
The program successfully creates an Employee object and displays the employee's details and current work using instance methods.

