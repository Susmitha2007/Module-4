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

import math

class cse:
  
    def mech(self, radius):
      
        """Calculate the area of a circle"""
        
        area = math.pi * (radius ** 2)
        
        return area

print("\nCircle Area Calculator")

radius = float(input("\nEnter the radius of the circle: "))

circle = cse()

area = circle.mech(radius)

print("\nCalculation Results:")

print(f"Radius entered: {radius}")

print(f"Area of circle: {area:.2f}\n")

## Output

![Screenshot 2025-04-30 153704](https://github.com/user-attachments/assets/dc98ab10-3175-4206-b06d-74e9d9be3174)


## Result

This program is successfully executed.
