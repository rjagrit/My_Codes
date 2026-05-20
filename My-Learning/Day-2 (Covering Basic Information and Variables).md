## Basic Concepts in Python
- To use comments in Python, use the hash '#' symbol
<img width="1015" height="247" alt="image" src="https://github.com/user-attachments/assets/72fab00e-2132-4210-9b15-711e3a608bb9" />

- Lowercase in print statements — e.g., print("hello, world!") not print("Hello, World!")
- Use \n for new lines — e.g., print("line one\nline two")
- Use clear before running — to get a clean terminal view in VS Code

## How Python Code Executes
1. Python code runs line by line (interpreter-based)
2. No need to compile manually- interpreter handles it.
3. Each Line was converted into bytecode and then executed by PVM (Python Virtual Machine)
4. Error will stop execution immediately. (Below Example showing Execution will stop when an error is encountered)
<img width="791" height="322" alt="image" src="https://github.com/user-attachments/assets/629580f5-719b-4231-aebb-c835fb4a85fa" />

## Variables & Memory Concept
1) Variables = Names that store a value in the memory (Choose a name of a variable that has some meaning so that it can be understood by anyone who reads it)
2) In Python, variables are used to store data that can be referenced and manipulated during program execution.
   - Ex: We are trying to store our name and age in a variable and print them, but found an -‼️(error that integer values cannot be concatenated). 
<img width="1187" height="372" alt="image" src="https://github.com/user-attachments/assets/9e23512e-3544-4412-9831-ba0911cd64bf" />

- ✅We have to convert them into a string; we make use of the str() method. After converting the Integer value into a string, we get the output as:
<img width="1195" height="240" alt="image" src="https://github.com/user-attachments/assets/f0b194c9-3f62-4a72-b000-03c62447aaf0" />

3) Python automatically decides the Data type
4) Variables are references (labels) pointing to memory objects.

### Q. How to find/check memory location of a variable
- We can use id() method to check the memory location of a variable
<img width="1127" height="502" alt="image" src="https://github.com/user-attachments/assets/2a2aba99-cf9b-4ee6-9076-d570f8dff103" />
