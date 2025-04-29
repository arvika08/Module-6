# Exp.No:6.b
## Create a parent class vehicle with the following methods show(),max_speed,change_gear() inherit the car class from the vehicle class,where the car class methods max_speed(),change_gear() override the same methods of base class  using method overriding

### AIM  
To write a Python program to create a parent class vehicle with the following methods show(),max_speed,change_gear() inherit the car class from the vehicle class,where the car class methods max_speed(),change_gear() override the same methods of base class  using method overriding.

### ALGORITHM

Define the Vehicle Class:

The Vehicle class has an __init__ method that initializes three properties: name, color, and price.

It also has three methods:

show(): Prints the details of the vehicle.

max_speed(): Prints the maximum speed of the vehicle (default 150).

change_gear(): Prints a message about changing gears (default 6 gears).

Define the Car Class:

The Car class inherits from the Vehicle class.

It overrides the max_speed() method to display the car's specific maximum speed (240).

It also overrides the change_gear() method to display the car’s specific gear-changing behavior (7 gears).

Create Instances of Car and Vehicle:

An object car of class Car is created with the name "Car x1", color "Red", and price 20000.

An object vehicle of class Vehicle is created with the name "Truck x1", color "white", and price 75000.

Call Methods:

For the car object, show(), max_speed(), and change_gear() methods are called. The max_speed() and change_gear() methods of the Car class are invoked, which override the methods from the Vehicle class.

For the vehicle object, show(), max_speed(), and change_gear() methods are called. The max_speed() and change_gear() methods from the Vehicle class are invoked.

### PROGRAM
class Vehicle:

    def __init__(self, name, color, price):
        self.name = name
        self.color = color
        self.price = price

    def show(self):
        print('Details:', self.name, self.color, self.price)

    def max_speed(self):
        print('Vehicle max speed is 150')

    def change_gear(self):
        print('Vehicle change 6 gear')


class Car(Vehicle):

    def max_speed(self):
        print('Car max speed is 240')

    def change_gear(self):
        print('Car change 7 gear')

car = Car('Car x1', 'Red', 20000)

car.show()

car.max_speed()

car.change_gear()

vehicle = Vehicle('Truck x1', 'white', 75000)

vehicle.show()

vehicle.max_speed()  

vehicle.change_gear() 


### OUTPUT
![image](https://github.com/user-attachments/assets/651ff0f7-e217-435c-8867-c7b8410e914e)


### RESULT
Thus, parent class vehicle with the following methods show(),max_speed,change_gear() inherit the car class from the vehicle class,where the car class methods max_speed(),change_gear() override the same methods of base class using method overriding was implemented successfully.

