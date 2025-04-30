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

lines = [
  
    "The tiger ran through the trees.",
    
    "A deer leapt over a log.",
    
    "Tigers are stealthy animals.",
    
    "Birds flew across the sky."
    
]

count = 0

for line in lines:
  
    if not line.lstrip().startswith('T'):
      
        count += 1

print("Number of lines that do NOT start with 'T':", count)

## Output

![Screenshot 2025-04-30 155917](https://github.com/user-attachments/assets/5bed0f57-6ecd-4bab-bea2-d434e99a2db6)


## Result

This program is successfully executed.
