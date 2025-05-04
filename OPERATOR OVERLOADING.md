# Exp.No:27  
## Operator Overloading

---

### AIM  
To write a  Python program for simply using the overloading operator for adding two objects.

---

### ALGORITHM

1. **Start**
2. Define a class `Add` with:

   * `__init__` method to accept four inputs (`a`, `b`, `c`, `d`)
   * `add` method to:

     * Add `a` and `b` (integer addition)
     * Concatenate `c` and `d` (string concatenation)
3. Take input for `a` (integer), `b` (integer), `c` (string), and `d` (string)
4. Create an object of class `Add`
5. Call the `add` method to display the sum of integers and concatenated strings
6. **End**


---

### PROGRAM

```
Reg no-212223070007
Nmae-Gopinath G

class Add:
    def __init__(self,a,b,c,d):
        self.a=a
        self.b=b
        self.c=c
        self.d=d
    def add(self):
        print(": ",self.a+self.b)
        print(": ",self.c+self.d)
a=int(input())
b=int(input())
c=input()
d=input()
x=Add(a,b,c,d)
x.add()
```

### OUTPUT

![image](https://github.com/user-attachments/assets/e1f62d7b-51e3-4fce-83ec-13059818b392)


### RESULT
Thus the Python program for simply using the overloading operator for adding two objects was executed successfully.
