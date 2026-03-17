# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

try:
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    result = a / b
    print("Result:", result)

except ZeroDivisionError:
    print("Error: Division by zero is not allowed")

except ValueError:
    print("Error: Invalid input")

finally:
    print("Program completed")

```

### OUTPUT

Enter first number: 10
Enter second number: 0
Error: Division by zero is not allowed
Program completed

### RESULT

Exception handling is performed successfully to handle runtime errors.
