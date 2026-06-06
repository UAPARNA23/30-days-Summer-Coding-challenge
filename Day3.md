<img width="818" height="412" alt="image" src="https://github.com/user-attachments/assets/80c51193-1068-488a-a9ba-1c0e4dbc1cdc" />

1. ```python
   # Checking divisibility by both 3 and 5
   num = int(input("Enter a number: "))
   if num % 3 == 0 and num % 5 == 0:
    print("The number is divisible by both 3 and 5")
   else:
    print("The number is not divisible by both 3 and 5")
   ```

2. ```python
   # ATM transaction processing rule
   available_balance = 5000
   withdrawal_amount = float(input("Enter withdrawal amount: "))
   if withdrawal_amount <= available_balance:
    available_balance -= withdrawal_amount
   print("Withdrawal successful! Remaining balance:", available_balance)
   else:
    print("Transaction rejected: Insufficient balance.")
   ```

3. ```python
   # Admission qualification check
   marks = int(input("Enter student marks: "))
   has_sports_certificate = input("Do you have a sports quota certificate? (yes/ no): ").strip().lower() == 'yes'
   if marks >= 70 or has_sports_certificate:
    print("Eligible for admission.")
   else:
    print("Not eligible for admission.")
   ```

4. ```python
   # Leap year verification rule
   year = int(input("Enter year: "))
   if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(year, "is a leap year.")
   else:
    print(year, "is not a leap year.")
   ```
