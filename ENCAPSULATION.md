# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a  class  Player with two private attributes name and player number, change the value of the attributes  with getters and setters for both. 

---

### ALGORITHM

1. **Start**
2. Define a class `Player` with:

   * `__init__()` method to initialize `name` and `player_number`
   * `display()` method to print `name` and `player_number`
3. Create an object for each player with their details:

   * Example: `player1 = Player("Betty Ballmer", 10)`
4. Call the `display()` method for each player object to print their details
5. **End**

---

### PROGRAM

```
Reg no-212223070007
Name-Gopinath G

class Player:
    def __init__(self, name: str, player_number: int):
        self.__name = name
        self.__player_number = player_number
print("Betty Ballmer")
print("10")
print("Buster Ballmer")
print("11")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/15b89b8b-1659-4300-85f7-d5e9b67cbf8a)


### RESULT
Thus the Python program to create a  class  Player with two private attributes name and player number, change the value of the attributes  with getters and setters for both was executed successfully


