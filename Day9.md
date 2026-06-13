<img width="1080" height="456" alt="image" src="https://github.com/user-attachments/assets/494a2203-21be-4848-8645-f6ebbbc1ac33" />

1. ```python
   # Optimized Prime Checker function targeting O(√n) time complexity
   def is_prime(n):
    if n <= 1:
    return False
       i = 2
    while i * i <= n:
    if n % i == 0:
    return False
           i += 1
    return True
    # Testing the function
    num = 29
    print(f"Is {num} prime? {is_prime(num)}")
   ```

2. ```python
   # Function to print all primes within a given range [start, end]
   def print_primes_in_range(start, end):
    for num in range(start, end + 1):
     if num > 1:
               is_current_prime = True
    # Embedded check up to root factor boundary
               i = 2
               while i * i <= num:
                if num % i == 0:
                       is_current_prime = False
                       break
                i += 1
               if is_current_prime:
                print(num, end=" ")
    print()
    # Newline cleanly terminating output
    # Execute range sweep
    print_primes_in_range(10, 50)
   ```

3. ```python
   # Efficient Euclidean algorithm Implementation
   def compute_gcd(a, b):
    while b > 0:
           a, b = b, a % b
   return a
   # Testing sample numbers
   num1, num2 = 36, 60
   print(f"GCD of {num1} and {num2} is: {compute_gcd(num1, num2)}")
   ```

4. ```python
   # Value swapping without extra auxiliary space variable allocation
   a = 15
   b = 27
   # Performance arithmetic steps
   a = a + b  # a now stores total combined sum (15 + 27 = 42)
   b = a - b  # b derives original value of a (42 - 27 = 15)
   a = a - b  # a derives original value of b (42 - 15 = 27)
   print(f"After arithmetic swap -> a: {a}, b: {b}")
   ```
