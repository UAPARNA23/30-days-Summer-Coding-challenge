<img width="896" height="644" alt="image1" src="https://github.com/user-attachments/assets/79473831-8acc-4639-951b-85bca899f043" />

1. ```python
   print("Let's start the challenge, I will stay consistent")
   ```

2.  ```python
    name = input("Enter your name: ") 
    print("Welcome,", name, "! Glad to have you here.")
    ```

3. ```python
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
   # Arithmetic calculation
    total_sum = num1 + num2
   # Displaying the final result
    print("The sum of the two numbers is:", total_sum)
   ```

4. ```python
   # Fetching numeric inputs
   dividend = int(input("Enter the dividend (Number to divide): "))
   divisor = int(input("Enter the divisor (Number to divide by): "))
   # Calculating remainder using the modulo operator (%)
   remainder = dividend % divisor
   print("The remainder of the division operation is:", remainder)
   ```

5. ```python
   # Gathering 3 distinct inputs
   n1 = float(input("Enter first number: "))
   n2 = float(input("Enter second number: "))
   n3 = float(input("Enter third number: "))
   # Parentheses isolate the sum prior to dividing
   average = (n1 + n2 + n3) / 3
   print("The calculated average value is:", average)
   ```

6. ```python
   # Prompting for two initial variable states
   x = input("Enter value for variable X: ")
   y = input("Enter value for variable Y: ")
   print("Before Swapping -> X:", x, "| Y:", y)
   # Pythonic elegant swapping logic
   x, y = y, x
   print("After Swapping  -> X:", x, "| Y:", y)
   ```

7. ```python
   # Collecting test scores across five subjects
   sub1 = float(input("Enter marks for Subject 1: "))
   sub2 = float(input("Enter marks for Subject 2: "))
   sub3 = float(input("Enter marks for Subject 3: "))
   sub4 = float(input("Enter marks for Subject 4: "))
   sub5 = float(input("Enter marks for Subject 5: "))
   # Performing operations
   total_obtained = sub1 + sub2 + sub3 + sub4 + sub5
   percentage = (total_obtained / 500) * 100
   # Output Summary print("--- Results ---")
   print("Total Marks Secured:", total_obtained, "/ 500")
   print("Aggregate Percentage:", percentage, "%")
   ```

8. ```python
   # Capturing metric state in Celsius
   celsius = float(input("Enter temperature in Celsius (°C): "))
   # Implementing conversion formula
   fahrenheit = (celsius * 9 / 5) + 32
   print(celsius, "°C translates to", fahrenheit, "°F")
   ```

9. ```python
   # Capturing metric state in Fahrenheit
    fahrenheit = float(input("Enter temperature in Fahrenheit (°F): "))
   # Enforcing parentheses to ensure correct subtraction priority
   celsius = (fahrenheit - 32) * 5 / 9
   print(fahrenheit, "°F translates to", celsius, "°C")
   ```

10. ```python
    # Collecting dimensions of the 3D solid cuboid
    length = float(input("Enter the Length of the cuboid: "))
    breadth = float(input("Enter the Breadth of the cuboid: "))
    height = float(input("Enter the Height of the cuboid: "))
    # Calculating 3D volumetric space
    volume = length * breadth * height
    print("The total structural volume of the cuboid is:", volume, "cubic units")
    ```
