# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy
x=eval(input())
y=eval(input())
print("Printing Original array")
og_arr = numpy.array(x)
print (og_arr)
print("Array after deleting column 2 on axis 1")
a=numpy.delete(og_arr,1,axis=1)
print(a)
print("Array after inserting column 2 on axis 1")
print (numpy.insert(a,1,y,axis=1))
```
## Output
<img width="1183" height="375" alt="image" src="https://github.com/user-attachments/assets/c332c8fc-021c-4e43-aeee-63246772c03d" />

## Result
program has been successfully completed
