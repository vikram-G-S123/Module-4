# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

d = {}

n = int(input("Enter number of elements: "))

for i in range(n):
    key = input("Enter key: ")
    value = input("Enter value: ")
    d[key] = value

print("Dictionary:", d)
print("Size of dictionary:", len(d))



```

### OUTPUT

Enter number of elements: 3
Enter key: a
Enter value: 10
Enter key: b
Enter value: 20
Enter key: c
Enter value: 30
Dictionary: {'a': '10', 'b': '20', 'c': '30'}
Size of dictionary: 3


### RESULT

The size of the dictionary is determined successfully.
