# Simple-Calculator
Build a console calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

### **Detailed Description and Working Procedure**

The **Simple Calculator** is a console-based Java application that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. Users provide two numbers and an operation to calculate the result. This program introduces core programming concepts like user input, decision-making, and arithmetic operations.

---

### **1. Purpose of the Program**
The program acts as a basic calculator that accepts user input, performs the specified arithmetic operation, and displays the result. Its goal is to provide an easy and interactive way for users to compute mathematical operations while handling errors gracefully (e.g., division by zero or invalid operations).

### **2. Working Procedure**
1. **Program Initialization**:
   - The program begins by creating a `Scanner` object to read user input.
   - It displays a title message: `--- Simple Calculator ---`.

2. **Input Collection**:
   - The user is prompted to input:
     1. The first number (`num1`).
     2. The second number (`num2`).
     3. An operator (`+`, `-`, `*`, `/`).

3. **Operation Execution**:
   - The program uses a `switch` statement to identify and execute the appropriate arithmetic operation based on the operator entered by the user:
     - Addition (`+`): Adds `num1` and `num2`.
     - Subtraction (`-`): Subtracts `num2` from `num1`.
     - Multiplication (`*`): Multiplies `num1` and `num2`.
     - Division (`/`): Divides `num1` by `num2`, with a check to ensure `num2` is not zero.

4. **Error Handling**:
   - If the operator is invalid (not one of `+`, `-`, `*`, `/`), an error message is displayed.
   - If division by zero is attempted, a specific error message is shown, and the calculation is skipped.

5. **Result Display**:
   - If the operation is valid, the result of the calculation is displayed to the user.

6. **Program Termination**:
   - The program closes the `Scanner` and ends.

### **3. Example Workflow**

#### Case 1: Valid Addition Operation
```
--- Simple Calculator ---
Enter the first number: 5
Enter the second number: 3
Enter an operation (+, -, *, /): +
The result is: 8.0
```

#### Case 2: Division by Zero
```
--- Simple Calculator ---
Enter the first number: 10
Enter the second number: 0
Enter an operation (+, -, *, /): /
Error: Division by zero is not allowed.
```

#### Case 3: Invalid Operation
```
--- Simple Calculator ---
Enter the first number: 7
Enter the second number: 4
Enter an operation (+, -, *, /): ^
Error: Invalid operation.

### **Conclusion**
The **Simple Calculator** is an excellent beginner-level project that combines user interaction, decision-making, and arithmetic operations. It offers practical insights into program design and handling real-world input scenarios.
