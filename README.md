# 🚗 Car Rental System

A simple Python-based program to calculate the **total charge** for a rental car based on customer input including car type and number of rental days. Ideal for understanding conditionals, user input, and basic business logic in Python.

---

## 📌 Description

This program determines the **total rental charge** for a customer based on the following rules:

- **Base charge** for any rental: `$65`
- **Car types** and their additional daily fees:
  - **Compact**: No extra fee
  - **Standard**: +$10/day
  - **SUV**: +$15/day
  - **Van**: +$25/day
- If the rental is for **more than 7 days**, a **20% discount** is applied to the total charge.

The program:
- Accepts **customer name**, **car type**, and **rental duration (days)**
- Calculates and applies extra charges and discount (if applicable)
- Displays a summary of the transaction with the **final total**

---

## 🧪 Sample Input

Please enter your name: Alice
Please enter the car type: SUV
Please enter the days of rent: 10

### 💸 Output

Name: Alice
Car Type: SUV
Days of Rent: 10 days
Discount: $ 160.0
Total Bill: $ 640.0
