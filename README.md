
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/cf9296ba-8410-4592-8df0-bac4afd7fdba" />

# Level-3-code-karaoke
Level 3 questions for code karaoke event, there are 2 scenario based  fork and upload in git hub 

# 1st Question :
1.You are building a billing system for a small café.
The café sells:
•	Coffee → ₹60
•	Sandwich → ₹120
•	Cake → ₹80
You need to write a Python program that:
1.	Asks the user what they want to order.
2.	Asks how many of that item they want.
3.	Calculates and displays the total bill.

menu = {
    "coffee": 60,
    "sandwich": 120,
    "cake": 80
}

print("Welcome to the Café!")
print("Menu:")
for item, price in menu.items():
    print(f"{item.capitalize()} - ₹{price}")
order = input("\nWhat would you like to order? ").lower()

if order in menu:
    quantity = int(input(f"How many {order}s would you like? "))
    total = menu[order] * quantity
    print(f"\nYour total bill for {quantity} {order}(s) is ₹{total}.")
else:
    print("\nSorry, that item is not on the menu.")

# OUTPUT:![WhatsApp Image 2025-11-08 at 11 23 31_1babef42](https://github.com/user-attachments/assets/830ee6ab-f1f4-4b99-8694-0016028c332f)

![WhatsApp Image 2025-11-08 at 11 23 08_671e83c8](https://github.com/user-attachments/assets/9348c548-1416-414c-85ca-aed11ca0f647)


# Question 2:
2. You’re designing a program for a college portal that evaluates a student’s final grade based on their marks in 3 subjects.
Rules:
•	If the average is 90 or above → Grade A+
•	If the average is 75–89 → Grade A
•	If the average is 60–74 → Grade B
•	If the average is 40–59 → Grade C
•	Below 40 → Fail
The program should:
1.	Take marks for 3 subjects from the user
2.	Calculate the average
3.	Print the average and the grade
________________________________________
# Example Input / Output:
Enter mark for Subject 1: 85
Enter mark for Subject 2: 78
Enter mark for Subject 3: 90
Average = 84.33
Grade = A





# Code:mark1 = float(input("Enter mark for Subject 1: "))
mark2 = float(input("Enter mark for Subject 2: "))
mark3 = float(input("Enter mark for Subject 3: "))

average = (mark1 + mark2 + mark3) / 3

if average >= 90:
    grade = "A+"
elif average >= 75:
    grade = "A"
elif average >= 60:
    grade = "B"
elif average >= 40:
    grade = "C"
else:
    grade = "Fail"

print(f"Average = {average:.2f}")
print(f"Grade = {grade}")

# OUTPUT:
![WhatsApp Image 2025-11-08 at 11 15 18_1183f677](https://github.com/user-attachments/assets/7fe81f28-6453-46c9-bf0a-a004da8373b5)
