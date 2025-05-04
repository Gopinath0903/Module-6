# Exp.No:28  
## Abstraction

---

### AIM  
To write a Python program to import the abc module to create the abstract base class. Create the Car class that inherit the ABC class and define an abstract method named mileage(). then inherit the base class from the three different subclasses and implement the abstract method differently. Create the objects to call the abstract method.

---

### ALGORITHM

1. **Start**
2. **Import** the `ABC` and `abstractmethod` from the `abc` module.
3. **Define** an abstract class `Car` with an abstract method `mileage()`.
4. **Create** a subclass `Tesla` that:

   * Inherits from `Car`
   * Implements the `mileage()` method
5. **Create** a subclass `Ford` that:

   * Inherits from `Car`
   * Implements the `mileage()` method
6. **Create** a subclass `BMW` that:

   * Inherits from `Car`
   * Implements the `mileage()` method
7. **Create objects** of `Tesla`, `Ford`, and `BMW`.
8. **Call** the `mileage()` method on each object to display the mileage information.
9. **End**


---

### PROGRAM

```
Reg no-212223070007
Name-Gopinath G

from abc import ABC, abstractmethod
class Car(ABC):

    @abstractmethod
    def mileage(self):
        pass
class Tesla(Car):
    def mileage(self):
        print("Tesla mileage is 300 miles per charge.")
class Ford(Car):
    def mileage(self):
        print("Ford mileage is 25 miles per gallon.")
class BMW(Car):
    def mileage(self):
        print("BMW mileage is 30 miles per gallon.")
tesla_car = Tesla()
ford_car = Ford()
bmw_car = BMW()
tesla_car.mileage()
ford_car.mileage()
bmw_car.mileage()


```

### OUTPUT

![image](https://github.com/user-attachments/assets/1a21fb48-07d1-4018-acfe-fad2a7767d1e)


### RESULT
Thus the import the abc module to create the abstract base class. Create the Car class that inherit the ABC class and define an abstract method named mileage(). then inherit the base class from the three different subclasses and implement the abstract method differently. Create the objects to call the abstract method was  executed successfully
