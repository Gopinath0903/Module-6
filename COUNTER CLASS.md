# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
Reg no-212223070007
Name-Gopinath G

class Counter:
    def __init__(self):
        self.value = 0  # Initialize counter to 0

    def increment(self):
        self.value += 1  # Increase counter by 1

    def get_value(self):
        return self.value  # Return current counter value

    def reset(self):
        self.value = 0  # Reset counter to 0
if __name__ == "__main__":
    counter = Counter()
    print("Initial value:", counter.get_value())
    
    counter.increment()
    counter.increment()
    print("After incrementing twice:", counter.get_value())
    
    counter.reset()
    print("After reset:", counter.get_value())

```

### OUTPUT
![image](https://github.com/user-attachments/assets/dc9be8fb-0fcd-4add-85a2-b1013b8ced7d)


### RESULT
Thus the python program to create a `Counter` class that can increment the value of a counter  was executed successfully
