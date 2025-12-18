# Cashier Change Utility

A precise and efficient **Cashier Change Utility** designed to calculate the exact breakdown of currency notes and coins required for any given transaction. This tool minimizes the number of units returned, simulating a real-world professional cashier experience.

## 🚀 Overview

The **Cashier Change** project solves the fundamental "Change-Making Problem." It takes a total amount due and the amount paid by the customer, then instantly calculates the balance and provides a detailed denomination breakdown (e.g., how many $20s, $10s, $5s, etc.).

### Key Objectives:
* **Accuracy:** Eliminate manual calculation errors in retail or point-of-sale scenarios.
* **Optimization:** Use the "Greedy Algorithm" approach to ensure the fewest possible bills and coins are handed back.
* **Simplicity:** A clean logic-based tool that can be integrated into larger POS (Point of Sale) systems.

## ✨ Features

* **Instant Calculation:** Real-time processing of change for any transaction amount.
* **Denomination Breakdown:** Lists exactly which bills and coins to return to the customer.
* **Error Handling:** Validates if the amount paid is sufficient to cover the total cost.
* **Flexible Currency Logic:** Easily adaptable to different currency systems (USD, PKR, EUR, etc.).
* **Clean UI:** Simple, intuitive interface for quick data entry and results.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3
* **Logic:** JavaScript (ES6+)
* **Styling:** Clean, responsive CSS or Tailwind CSS

## 📥 Installation & Usage

Since this is a lightweight utility, you can run it directly in your browser.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Taimoorr15/Cashier-Change.git](https://github.com/Taimoorr15/Cashier-Change.git)
    cd Cashier-Change
    ```

2.  **Open the Project**
    Simply open `index.html` in your favorite web browser.

3.  **How to Use:**
    * Enter the **Bill Amount**.
    * Enter the **Cash Given** by the customer.
    * Click **Calculate** to see the total change and the specific notes/coins to return.

🧠 The Logic
-The system follows a standard currency breakdown logic:
-Calculate the total difference: Cash Paid - Total Bill.
-Iterate through available denominations from highest to lowest.
-Determine the maximum count of each denomination that fits into the remaining balance.
-Display the result to the user.

👨‍💻 Author

Taimoor

GitHub: https://github.com/Taimoorr15

If you like this project, give it a ⭐ — it helps more than you think.
