# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM 
Write Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary'

---

### ALGORITHM

1. Begin the program.
2. Create a class named pen.
3. Define a method stationary(self, r) inside the class pen that accepts a radius r as an argument.
4. Inside the stationary method:
  -> Calculate the area of a circle using the formula:
       -> [ \text{Area} = \pi \times r^2 ]
5. Prompt the user for an integer input to represent the radius of the circle.
6. Create an instance of the pen class and store it in the variable a.
7. Call the stationary method of the pen class
8. Terminate the program.

---

### PROGRAM

```
Reg.No: 212223090030
Name: Vijayalakshmi M P

class pen:
    r=int(input())
    a=3.141592*(r**2)
    def stationary(self):
        print(f"Area of circle: {round(self.a,2)}")
obj=pen()
obj.stationary()
```

### OUTPUT
<img width="1072" height="330" alt="image" src="https://github.com/user-attachments/assets/7cebd5ad-2e6e-488d-9bd2-66cbf86cf04e" />

### RESULT
Thus,a Python program to take the radius from the user and find the area of a circle are verified.
