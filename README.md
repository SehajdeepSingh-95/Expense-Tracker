# 💰 Expense Tracker

A simple **vanilla JavaScript** Expense Tracker that allows users to add, delete, and view expenses.  
All expenses are saved in **LocalStorage**, so data persists even after the page is refreshed.

---

## 🚀 Features
- ➕ **Add Expenses** – Enter an expense name and amount.
- ❌ **Delete Expenses** – Remove individual expenses from the list.
- 💾 **Persistent Data** – Expenses are saved using `localStorage`.
- 💰 **Total Calculation** – Displays the running total of all expenses.
- ⌨️ **Enter Key Support** – Press Enter to quickly add expenses.

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3** (Optional styling)
- **Vanilla JavaScript (ES6+)**
- **LocalStorage API**

---


---

## ⚙️ How It Works
1. Users enter an expense name and amount.
2. Clicking the **Add** button (or pressing Enter) saves the expense in an array.
3. The `updateExpenseList()` function dynamically updates the displayed list of expenses and recalculates the total.
4. **Delete** buttons remove items from the array and the list.
5. Data is saved to `localStorage` so expenses remain after refreshing the page.

---

## 🖥️ Setup & Usage
1. Clone or download the project files.
2. Make sure your HTML contains:
```html
<input type="text" id="expenseInput" placeholder="Expense Name" />
<input type="number" id="amountInput" placeholder="Amount" />
<button id="addButton">Add Expense</button>

<ul id="expenseList"></ul>
<p id="totalAmount">Total: $0.00</p>
