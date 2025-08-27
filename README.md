![Screenshot_2025-08-27-16-50-40-930_ru iiec pydroid3](https://github.com/user-attachments/assets/a0e870b4-ae25-49d4-a79f-c4ac4328b461)# Simple-Calculator
Coding with python 


# Student Report Card

# Taking inputs
name = input("Enter student name: ")
roll = input("Enter roll number: ")

math = float(input("Enter marks in Math: "))
science = float(input("Enter marks in Science: "))
english = float(input("Enter marks in English: "))
history = float(input("Enter marks in History: "))
computer = float(input("Enter marks in Computer: "))

# Calculations
total = math + science + english + history + computer
percentage = (total / 500) * 100  # since 5 subjects, each out of 100

# Grade system
if percentage >= 90:
    grade = "A+"
elif percentage >= 75:
    grade = "A"
elif percentage >= 60:
    grade = "B"
elif percentage >= 40:
    grade = "C"
else:
    grade = "Fail"

# Printing Report Card
print("\n----- REPORT CARD -----")
print("Name:", name)
print("Roll No:", roll)
print("Total Marks =", total)
print("Percentage =", round(percentage, 2), "%")
print("Grade =", grade)

