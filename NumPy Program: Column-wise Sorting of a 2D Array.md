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
dictionary = {
    'c': 'orange',
    'a': 'apple',
    'b': 'banana'
}

sorted_keys = dict(sorted(dictionary.items()))

sorted_values = dict(
    sorted(dictionary.items(), key=lambda item: item[1])
)

print("Original Dictionary:", dictionary)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
```

## Output

<img width="595" height="152" alt="601369305-2cce5635-8a90-4580-820e-2d8d00643966" src="https://github.com/user-attachments/assets/784b3043-5444-4b41-aa8b-0d8715361f75" />

## Result
Thus, the Python program to sort a dictionary by its keys and values was executed successfully and the output was verified.

