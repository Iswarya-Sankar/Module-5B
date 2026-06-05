# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program

```
import numpy as np

arr = np.array([[9, 3, 5],
                [2, 8, 1],
                [7, 4, 6]])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="285" height="240" alt="601370312-c7f4ce11-70db-4da4-a3c4-39fa635b347b" src="https://github.com/user-attachments/assets/c1b18c70-82e7-411f-951d-c6dbf7f1c64b" />

## Result

Thus, the NumPy program to sort the elements in each column of a given 2D array in ascending order was executed successfully and the output was verified.
