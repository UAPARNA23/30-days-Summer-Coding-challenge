<img width="930" height="698" alt="image" src="https://github.com/user-attachments/assets/d5ea5a94-195b-4d13-b8ce-e3a0555c93c9" />

1. ```python
   # Taking a numeric input and checking its positivity
   num = float(input("Enter a number: "))
   if num > 0:
   print("The number is positive.")
   ```

2. ```python
   # Using the modulo operator to verify clean divisibility by 5
   num = int(input("Enter an integer: "))
   if num % 5 == 0:
   print("The number is divisible by 5.")
   else:
   print("The number is not divisible by 5.")
   ```

3. ```python
   # Checking age entry against the legal voting milestone
   age = int(input("Enter your age: "))
   if age >= 18:
   print("You are eligible to vote.")
   else:
   print("You are not eligible to vote.")
   ```

4. ```python
   # Distinguishing between even and odd integers via remainder tracking
   num = int(input("Enter a number: "))
   if num % 2 == 0:
   print("The number is even.")
   else:
   print("The number is odd.")
   ```

5. ```python
   # Evaluating two distinct inputs to print the maximum value
   num1 = float(input("Enter first number: "))
   num2 = float(input("Enter second number: "))
   if num1 > num2:
   print(f"{num1} is larger.")
   else:
   print(f"{num2} is larger.")
   ```

6. ```python
   # Comparing student marks against a minimum pass cutoff
   marks = float(input("Enter student's marks: "))
   if marks >= 35:
   print("Result: Passed")
   else:
   print("Result: Failed")
   ```

7. ```python
   # Chaining conditions to determine multi-state number signs
   num = float(input("Enter a number: "))
   if num > 0:
   print("The number is positive.")
   elif num < 0:
   print("The number is negative.")
   else:
   print("The number is zero.")
   ```

8. ```python
   # Multi-tier age categorization using a clean condition cascade
   age = int(input("Enter age: "))
   if age < 13:
   print("Category: Child")
   elif age <= 19:
   print("Category: Teenager")
   elif age <= 59:
   print("Category: Adult")
   else:
   print("Category: Senior Citizen")
   ```

9. ```python
   # Combining distinct comparisons with logical operators to extract the maximum
   a = float(input("Enter first number: "))
   b = float(input("Enter second number: "))
   c = float(input("Enter third number: "))
   if a >= b and a >= c:
   print(f"{a} is the largest number.")
   elif b >= a and b >= c:
   print(f"{b} is the largest number.")
   else:
   print(f"{c} is the largest number.")
   ```

10. ```python
    # Processing transaction totals and calculating reward discounts conditionally
    purchase_amount = float(input("Enter total purchase amount (₹): "))
    if purchase_amount > 5000:
     discount = purchase_amount * 0.20
     print("Eligible for a 20% discount!")
    else:
     discount = 0.0
    final_payable = purchase_amount - discount
    print(f"Final amount payable: ₹{final_payable:.2f}")
    ```
