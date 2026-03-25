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

student_data1 = pd.DataFrame({
    'student_id': ['S1', 'S2', 'S3'],
    'name': ['Alice', 'Bob', 'Charlie'],
    'marks': [85, 92, 78]
})

student_data2 = pd.DataFrame({
    'student_id': ['S4', 'S5', 'S6'],
    'name': ['David', 'Eve', 'Frank'],
    'marks': [88, 76, 95]
})

combined_data = pd.concat([student_data1, student_data2], axis=0)

print("Combined DataFrame:")
print(combined_data)
```

## Output
<img width="442" height="213" alt="568185638-76dcb85a-cdca-4326-87fc-2865c2fc2ff8" src="https://github.com/user-attachments/assets/049044df-5ab7-4d2f-8277-66191a4c385a" />

## Result
Thus,the program has been executed successfully.
