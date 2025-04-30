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

original_dict = {
  
    'banana': 'fruit',
    
    'apple': 'fruit',
    
    'carrot': 'vegetable',
    
    'date': 'fruit',
    
    'eggplant': 'vegetable'
    
}

sorted_by_keys = dict(sorted(original_dict.items()))

sorted_by_values = dict(sorted(original_dict.items(), key=lambda item: item[1]))

print("Original Dictionary:")

print(original_dict)

print("\nDictionary Sorted by Keys:")

print(sorted_by_keys)

print("\nDictionary Sorted by Values:")

print(sorted_by_values)

## Sample Output

![Screenshot 2025-04-30 154409](https://github.com/user-attachments/assets/2174d79f-7195-47ec-99db-d52016612f6c)


## Result

This program is successfully executed.

