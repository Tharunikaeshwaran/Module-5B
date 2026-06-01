# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
student_data1 = {
    'id': [1, 2, 3],
    'name': ['KimNamjoon', 'MinYoongi', 'Kimtaehyung'],
    'marks': [85, 90, 78]
}
df1 = pd.DataFrame(student_data1)
student_data2 = {
    'id': [4, 5, 6],
    'name': ['JungHoseok', 'Seok Jin', 'JeonJungkook'],
    'marks': [88, 92, 80]
}
df2 = pd.DataFrame(student_data2)
combined_df = pd.concat([df1, df2], axis=0,ignore_index=True)
print("Combined DataFrame:\n")
print(combined_df)

```

## Output
<img width="834" height="310" alt="image" src="https://github.com/user-attachments/assets/231f4da8-b945-427b-a8b1-a0a5d1ce5635" />

## Result
program has been successfully completed
