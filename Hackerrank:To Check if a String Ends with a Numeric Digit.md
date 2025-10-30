# 🔍 Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

## 🎯 Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Input** a string from the user.
3. **Access** the last character using indexing (`string[-1]`).
4. **Check** if the last character is a digit using the `.isdigit()` method.
5. **If true**, print that the string ends with a number.
6. **Else**, print that the string does not end with a number.
7. **End the program.**

---

## 💻  Program
    text = input("Enter a string: ")
    if text[-1].isdigit():
        print("The string ends with a number.")
    else:
        print("The string does not end with a number.")
## Output
<img width="804" height="180" alt="image" src="https://github.com/user-attachments/assets/22e75f2e-a5ff-48e7-9d52-5de8a701bac0" />

## Result
Thus the program executed successfully .
