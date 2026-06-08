<img width="1136" height="1280" alt="image" src="https://github.com/user-attachments/assets/3df3791a-5adb-45c8-b692-0b1f1935795b" />

1. ```python
   # Function to calculate the sum of first N natural numbers
   def sum_of_natural_numbers(N):
     total_sum = 0
     # Loop from 1 to N
     for i in range(1, N + 1):
       total_sum += i # Adding the current number to the running total
     print(total_sum)
   ```

2. ```python
   # Function to print the multiplication table of N
   def multiplication_table(N):
     # Loop from 1 to 10
     for i in range(1, 11):
       product = N * i
       # Printing the formatted table row
       print(f"{N} x {i} = {product}")
   ```

3. ```python
   # Function to count total digits in an integer
   def count_digits(N):
     count = 0
     if N == 0:
       return 1
     while N > 0:
       N = N // 10
       count += 1
     print(count)
   ```

4. ```python
   # Function to reverse the digits of an integer
   def reverse_number(N):
     reversed_num = 0
     while N > 0:
       last_digit = N % 10  # Extract the last digit
       reversed_num = (reversed_num * 10) + last_digit
       N = N // 10   # Remove the last digit from original N
     print(reversed_num)
   ```

5. ```python
   # Function to check if a number is prime
   def is_prime(N):
     if N <= 1:
       print("Not Prime")
       return
     # Check for factors up to the square root of N
     for i in range(2, int(N**0.5) + 1):
       if N % i == 0:
         print("Not Prime")
         break
     else:
       print("Prime Number")
   ```
