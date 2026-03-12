📘 Right-Aligned Number Triangle Pattern (Python)
📌 Overview

This Python program prints a right-aligned number triangle pattern using nested loops.
Each row displays numbers starting from 1 up to the current row number, while leading spaces keep the triangle right aligned.

This example helps beginners understand nested loops, pattern logic, and string formatting.

⚙️ Source Code
rows = 5 
for i in range(1, rows + 1):
    print(" " * (rows - i), end=" ")
    for j in range(1, i + 1):
        print(j, end=" ")
    print()
🧠 How It Works
1️⃣ Define Number of Rows
rows = 5

This determines the height of the triangle.

2️⃣ Outer Loop – Controls Rows
for i in range(1, rows + 1):

Runs from 1 to rows

Each iteration prints a new row

3️⃣ Print Leading Spaces
print(" " * (rows - i), end=" ")

Adds spaces before numbers

Ensures the triangle appears right aligned

4️⃣ Inner Loop – Prints Numbers
for j in range(1, i + 1):
    print(j, end=" ")

Prints numbers starting from 1

Ends at the current row number i

5️⃣ Move to Next Line
print()

After each row, this moves the cursor to the next line.

▶️ Sample Output
     1
    1 2
   1 2 3
  1 2 3 4
 1 2 3 4 5
🔑 Key Concepts Demonstrated

Nested loops

Pattern printing logic

String multiplication

Alignment using spaces

Loop-based number generation

⏱️ Time Complexity

O(n²)
The inner loop runs up to n times for each row.

🚀 Possible Enhancements
Reverse Number Triangle
for i in range(rows, 0, -1):
    for j in range(1, i + 1):
        print(j, end=" ")
    print()
Floyd’s Triangle
num = 1
for i in range(1, rows + 1):
    for j in range(i):
        print(num, end=" ")
        num += 1
    print()
📚 Learning Outcomes

After understanding this program, you will learn:

How to design number patterns

How nested loops control rows and columns

How spacing helps create aligned shapes in console output

<img width="622" height="772" alt="image" src="https://github.com/user-attachments/assets/e20a71e1-aa37-4834-b764-f6694ca46887" />
