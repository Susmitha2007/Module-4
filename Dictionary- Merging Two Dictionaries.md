## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

def merge(dict1, dict2):
  
    """Merge two dictionaries using the ** unpacking operator"""
    
    return {**dict1, **dict2}

dict1 = {'a': 1, 'b': 2}

dict2 = {'b': 3, 'c': 4}

merged_dict = merge(dict1, dict2)

print("Dictionary 1:", dict1)

print("Dictionary 2:", dict2)

print("\nMerged Dictionary:", merged_dict)

## Output

![Screenshot 2025-04-30 154018](https://github.com/user-attachments/assets/44e8e379-c3e6-46e1-b5b0-0d90cba13883)


## Result

This program is successfully executed.
