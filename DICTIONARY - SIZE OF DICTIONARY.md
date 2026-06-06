# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.
2. Import the getsizeof function from the sys module to measure the size of objects in bytes.
3. Create three dictionaries: dic1, dic2, and dic3 with different key-value pairs.
4. Use getsizeof() to calculate the memory size of each dictionary and store them in result1, result2, and result3.
5. Print the sizes of all three dictionaries in bytes using the print() function.
6. Terminate the program.

---

### PROGRAM

```
#Reg.No: 212223090030
#Name: Vijayalakshmi M P

from sys import getsizeof
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
result1 = getsizeof(dic1)
result2 = getsizeof(dic2)
result3 = getsizeof(dic3)
print("Size of dic1: ", result1, "bytes", sep='')
print("Size of dic2: ", result2, "bytes", sep='')
print("Size of dic3: ", result3, "bytes", sep='')
```

### OUTPUT
<img width="746" height="221" alt="image" src="https://github.com/user-attachments/assets/34db7bd4-3b35-4218-a800-6774add0c246" />

### RESULT
Thus, a Python program to print the size of a dictionary using getsizeof() from the sys module are verified.
