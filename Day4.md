<img width="1170" height="949" alt="image" src="https://github.com/user-attachments/assets/549a82c1-88c0-4c12-81a0-8dea3b851fc1" />

1. ```python
   # Iterating sequentially from 1 to 1000 using a for loop
   for i in range(1, 1001):
    print(i)
   ```

2. ```python
   # Taking integer input from the user dynamically
   N = int(input("Enter a number: "))
   # Looping 10 sequential times to generate formatting table rows
   for i in range(1, 11):
    print(f"{N} x {i} = {N * i}")
   ```

3. ```python
   # Taking the upper limit N as input
   N = int(input("Enter the value of N: "))
   # Iterating through every consecutive integer up to N
   for i in range(1, N + 1):
   # Checking if the number is completely divisible by 2 using an if statement
   if i % 2 == 0:
    print(i)
   ```

4. ```python
   # Capturing numerical terminal console input parameters
   N = int(input("Enter the value of N: "))
   # Iterating through every consecutive integer up to N
   for i in range(1, N + 1):
   # Evaluating if the number leaves an explicit remainder when split by 2
   if i % 2 != 0:
    print(i)
   ```

5. ```python
   # Acquiring core target factorial evaluation variables
   N = int(input("Enter a number: "))
   factorial = 1
   # Multiplying value blocks systematically sequentially into the tracker
   for i in range(1, N + 1):
    factorial *= i
   print(f"The factorial of {N} is {factorial}")
   ```
