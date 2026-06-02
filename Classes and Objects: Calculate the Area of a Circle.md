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
