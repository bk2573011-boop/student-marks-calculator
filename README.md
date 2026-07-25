# Student Marks Calculator
# Created by Bibha Kumari

print("===== Student Marks Calculator =====")

name = input("Enter student name: ")
math = int(input("Enter Maths marks: "))
python = int(input("Enter Python marks: "))
sql = int(input("Enter SQL marks: "))

total_marks = math + python + sql
percentage = total_marks / 3

print("\n----- Result -----")
print("Student Name:", name)
print("Total Marks:", total_marks, "/ 300")
print("Percentage:", round(percentage, 2), "%")

if percentage >= 40:
    print("Status: PASS ✅")
else:
    print("Status: FAIL ❌")

print("Thank you for using the calculator!")
