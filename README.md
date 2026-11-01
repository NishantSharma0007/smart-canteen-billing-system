# Smart Canteen Billing and Order Analyzer 🍔

## 📌 Project Overview

Smart Canteen Billing and Order Analyzer is a beginner-to-intermediate Python command-line application designed to manage food ordering and billing in a canteen.

The system displays a numbered food menu, accepts item selections and quantities, calculates the total bill, applies discounts based on the order amount, and generates a final receipt.

## 🎯 Project Objectives

- Learn Python control flow.
- Understand conditional statements.
- Practise for and while loops.
- Implement order management.
- Validate user input.
- Calculate bills and discounts.
- Generate a final billing receipt.

## ⚙️ Features

- Display numbered food menu.
- Select food items and quantities.
- Validate item numbers (1–5).
- Validate positive quantities.
- Calculate individual item costs.
- Add multiple items to one order.
- Automatically apply discounts.
- Generate a detailed receipt.
- Handle empty orders.

## 🍽️ Food Menu

| Item No. | Food Item | Price |
|---|---|---:|
| 1 | Veg Sandwich | ₹60 |
| 2 | Masala Dosa | ₹80 |
| 3 | Chole Rice | ₹90 |
| 4 | Paneer Roll | ₹100 |
| 5 | Tea | ₹20 |

## 💰 Discount System

| Order Subtotal | Discount |
|---|---:|
| ₹500 or above | 10% |
| ₹250–₹499.99 | 5% |
| Below ₹250 | No discount |

## 🛠️ Technologies Used

- Python 3
- VS Code / PyCharm
- Command Line Interface (CLI)

## 📚 Python Concepts Used

- Variables and Data Types
- Input and Output
- Type Conversion
- if, if-else, if-elif-else
- Nested if Statements
- for Loops
- while Loops
- range()
- break
- continue
- pass
- Nested Loops
- Arithmetic Operators

## 🚀 How to Run

1. Install Python 3.
2. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

3. Open the project folder in VS Code or PyCharm.
4. Run the Python program:

   ```bash
   python main.py
   ```

## 📊 Sample Output

```text
========== SMART CANTEEN ==========

1. Veg Sandwich - ₹60
2. Masala Dosa - ₹80
3. Chole Rice - ₹90
4. Paneer Roll - ₹100
5. Tea - ₹20

Choose item number: 4
Enter quantity: 2

Added: Paneer Roll x 2 = ₹200.00

Add another item? (y/n): y

Choose item number: 5
Enter quantity: 2

Added: Tea x 2 = ₹40.00

Add another item? (y/n): n

========== RECEIPT ==========

Paneer Roll x 2: ₹200.00
Tea x 2: ₹40.00

Subtotal: ₹240.00
Discount: ₹0.00
Final total: ₹240.00

Thank you!
```

## 📂 Project Structure

```text
smart-canteen-billing-system/
│
├── main.py
└── README.md
```

## 📖 Project Information

- **Project Type:** Python Mini-Project
- **Module:** Module 2 – Control Flow
- **Difficulty:** Beginner to Intermediate
- **Interface:** Command Line
- **External Packages:** None

## 👨‍💻 Author

Created as part of Python Technical Training.

## 📜 License

This project is intended for educational and learning purposes.
