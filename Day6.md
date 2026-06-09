<img width="904" height="882" alt="image" src="https://github.com/user-attachments/assets/d306d211-ee16-4ec9-a4bd-79b232967642" />

1. ```python
   # Iterating through the list and printing each element sequential layout
   for num in arr:
     print(num)
   ```

2. ```python
   # Accumulating the sum of all elements in the array
   total_sum = 0
   for num in arr:
       total_sum += num
   print(total_sum)
   ```

3. ```python
   # Finding the maximum value by sequential list comparison
   largest = arr[0]
   for num in arr:
    if num > largest:
           largest = num
   print(largest)
   ```

4. ```python
   # Finding the minimum value by sequential comparison tracking
   smallest = arr[0]
   for num in arr:
    if num < smallest:
          smallest = num
   print(smallest)
   ```

5. ```python
   # Counting elements that are perfectly divisible by standard integer 2
   even_count = 0
   for num in arr:
    if num % 2 == 0:
       even_count += 1
   print(even_count)
   ```

6. ```python
   # Filtering and displaying structural numbers not divisible evenly by 2
   for num in arr:
    if num % 2 != 0:
       print(num)
   ```

7. ```python
   # Counting elements that exceed the value threshold requirement of 10
   count_greater_than_10 = 0
   for num in arr:
    if num > 10:
      count_greater_than_10 += 1
   print(count_greater_than_10)
   ```

8. ```python
   # Generating a transformed list via linear loop iteration operations
   squared_arr = []
   for num in arr:
       squared_arr.append(num ** 2)
   print(squared_arr)
   ```

9. ```python
   # Iterating cleanly through a reversed slice variant copy of the list
   for num in arr[::-1]:
    print(num)
   ```

10. ```python
    # Computing arithmetic mean averages from sequential tracker totals
    total_sum = 0
    for num in arr:
        total_sum += num
    average = total_sum / len(arr)
    print(average)
    ```
