# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

class Circle:
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius * self.radius

r = float(input("Enter radius: "))
c = Circle(r)

print("Area of Circle:", c.area())


```

### OUTPUT

Enter radius: 5
Area of Circle: 78.5

### RESULT

The area of the circle is calculated successfully using class and object.



