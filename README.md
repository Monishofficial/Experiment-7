# Experiment-7

## AIM
### Write a python program for sorting and inspect for failures. 

## Algorithm
1. Start the program.

2. Get the number of elements from user

3. Get the elements to be sorted

4. Traverse the array and sort the elements one by one

5. Print the sorted array

6. Stop the program. 

## Program
#### Name: MONISH N
#### RegNo: 212223240097
```
n = int(input("Enter the number of elements: "))
arr = []
try:
    for i in range(n):
        a = int(input("Enter the element: "))
        arr.append(a)
    for i in range(n):
        for j in range(i + 1, n):
            if arr[i] > arr[j]:
                arr[i], arr[j] = arr[j], arr[i]
    print("The array after sorting:")
    for i in range(n):
        print(arr[i], end=' ')
except ValueError:
    print("Enter a valid number.")

```
## Output
<img width="605" height="257" alt="image" src="https://github.com/user-attachments/assets/d71a73b0-6f98-41fc-9b74-f4e62a6edb2e" />

## Result
Thus the python program for sorting and inspect for failures is executed successfully.


# Output
