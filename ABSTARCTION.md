# Exp.No:6.a
## Abstraction

### AIM  
To write an abstract class Animal with an abstract mathod move which can be implemented by the subclasses of the animal class.
### ALGORITHM

Define an Abstract Base Class (ani):

The class ani inherits from ABC, making it an abstract class.

An abstract method do() is defined using @abstractmethod. This means any subclass must implement the do() method.

Create Subclasses of ani:

hum, mon, dog, and lion are subclasses that inherit from ani.

Each subclass provides its own implementation of the do() method, as required by the abstract base class:

hum class: Defines do() to print "I can walk and run".

mon class: Defines do() to print "I can crawl".

dog class: Defines do() to print "I can bark".

lion class: Defines do() to print "I can roar".

Instantiate Objects and Call do():

Objects h, m, d, and l are created from the respective classes (hum, mon, dog, lion).

### PROGRAM
from abc import ABC,abstractmethod

class ani(ABC):

    @abstractmethod
    
    def do(self):
    
        pass
        
class hum(ani):

    def do(self):
    
        print("I can walk and run")
        
class mon(ani):

    def do(self):
    
        print("I can crawl")
        
class dog(ani):

    def do(self):
    
        print("I can bark")
        
class lion(ani):

    def do(self):
    
        print("I can roar")
h=hum()

h.do()

m=mon()

m.do()

d=dog()

d.do()

l=lion()

l.do()

### OUTPUT
![image](https://github.com/user-attachments/assets/ebec2401-f85a-4913-ae7b-775d689b3a5e)



### RESULT
Thus, an abstract class Animal with an abstract method move can be implemented by the subclasses of the animal class was implemented successfully.
