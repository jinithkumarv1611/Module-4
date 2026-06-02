# EX-1:
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```python
import math

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of Circle:", area)

r = float(input("Enter the radius: "))
obj = cse()
obj.mech(r)

DEVELOPED BY: JINITH KUMAR V
REGISTER NO: 212225040157
```

## Output
<img width="1211" height="396" alt="image" src="https://github.com/user-attachments/assets/f7a62b4b-f478-4dc3-877c-c7075bc2da65" />

## Result
Thus the given program executed Successfully.

# EX-2:
## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```python
def merge():
    dict1 = {'a': 10, 'b': 20, 'c': 30}
    dict2 = {'b': 40, 'd': 50}

    merged_dict = {**dict1, **dict2}

    print("Merged Dictionary:", merged_dict)

merge()
```

## Output
<img width="1473" height="311" alt="image" src="https://github.com/user-attachments/assets/8cc6371d-f904-49aa-b1ef-ef8ff29a6b4b" />

## Result
Thus the given program executed Successfully.

# EX-3:
# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```python
dictionary = {
    "banana": "yellow",
    "apple": "red",
    "grape": "purple",
    "orange": "orange"
}

# Sort by keys
sorted_keys = dict(sorted(dictionary.items()))

# Sort by values
sorted_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

print("Original Dictionary:", dictionary)
print("Dictionary Sorted by Keys:", sorted_keys)
print("Dictionary Sorted by Values:", sorted_values)
```

## Sample Output
<img width="1614" height="564" alt="image" src="https://github.com/user-attachments/assets/fc5d94df-b181-4651-8aa2-ee900535ed05" />

## Result
Thus the given program executed Successfully.

# EX-4:
# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```python
list1 = [10, 20, 30, 40]

try:
    print("Element:", list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="1259" height="263" alt="image" src="https://github.com/user-attachments/assets/46d2c214-5d68-4f1a-b631-ff27767b0f33" />

## Result
Thus the given program executed Successfully.

# EX-5:
# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```python
f=open("story.txt","r")
count = 0

for i in f:
  if i[0]!='T':
      count+=1
  print(count)
f.close()
```

## Output
<img width="518" height="455" alt="image" src="https://github.com/user-attachments/assets/9aacf1de-17a1-4036-b41d-7888cf3cc87f" />

## Result
Thus the given program executed Successfully.
