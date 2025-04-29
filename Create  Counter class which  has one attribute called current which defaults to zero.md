# Exp.No:6.e
## Create  Counter class which  has one attribute called current which defaults to zero

---

### AIM  
To Create  Counter class which  has one attribute called current which defaults to zero

### ALGORITHM

Define the Counter Class:

The Counter class has an __init__ method that initializes an instance variable current to 0. This variable holds the current count.

The increment() method increases the value of current by 1 each time it is called.

The value() method returns the current value of current.

The reset() method sets the value of current back to 0.

Create a Counter Object:

An object counter of the Counter class is instantiated.

Increment the Counter:

The increment() method is called three times, which increases the value of current from 0 to 3 in total.

Print the Counter's Value:

After calling increment() three times, the value() method is called, which returns the current value of current (which is now 3).

The result is printed using print(counter.value()).

### PROGRAM
class Counter:

    def __init__(self):
        self.current = 0

    def increment(self):
        self.current += 1

    def value(self):
        return self.current

    def reset(self):
        self.current = 0

counter = Counter()

counter.increment()

counter.increment()

counter.increment()

print(counter.value())

### OUTPUT
![image](https://github.com/user-attachments/assets/840c1ad6-6631-46db-835a-cd659a24b8a9)


### RESULT
Thus,  Counter class which  has one attribute called current which defaults to zero was implemented successfully.

