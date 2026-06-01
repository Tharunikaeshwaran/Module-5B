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
r= int(input())
c= int(input())
el= []
for i in range(r):
    a = list(map(int, input().split()))
    el.append(a)
arr = np.array(el)
s= np.sort(arr, axis=0)
print("Original Array:")
print(arr)
print("Sorted Array:")
print(s)


```

## Output
<img width="1026" height="782" alt="image" src="https://github.com/user-attachments/assets/d5acdfff-35ac-49ee-b621-ac39f85d1a35" />

## Result
program has been successfully completed
