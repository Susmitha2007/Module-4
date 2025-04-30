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

list1 = [10, 20, 30, 40, 50]

try:
  
    index = 5 
    
    element = list1[index]
    
    print(f"Element at index {index}: {element}")
    
except IndexError:
  
    print("You're out of list range")
    
    print(f"The list only has {len(list1)} elements (indices 0-{len(list1)-1})")
    
finally:
  
    print("\nOriginal list:", list1)
    
## Output

![Screenshot 2025-04-30 154753](https://github.com/user-attachments/assets/f5985e3d-31d6-448d-b8e6-27d7936b12f5)


## Result

This program is successfully executed.
