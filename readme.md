# Expense Tracker

A simple and responsive web app to track your income and expenses.  
Built with **Vanilla JavaScript** and **LocalStorage** for a fast, database-free experience.

## About

This app helps users monitor their financial activity by adding income and expense transactions.  
All data is stored locally in the browser and updates instantly.

## Features

- Real-time balance, income, and expense calculation
- Add income (positive values) and expenses (negative values)
- Transaction history with latest entries on top
- Delete transactions instantly
- Color indicators (green = income, red = expense)
- Data persistence using **LocalStorage**
- Responsive and modern UI design

## Tech Stack

- **HTML5** – structure
- **CSS3** – layout (Flexbox & Grid) and animations
- **JavaScript (ES6+)** – logic and data handling
- **Google Fonts (Poppins)** – typography
- **Intl.NumberFormat API** – currency formatting

## How to Use

1.  **Clone the repository:**

    ```
    git clone https://github.com/jimmy-ai2/Expense-Tracker.git
    ```

2.  Open `index.html` in your browser

3.  Add a transaction:
    - Enter a description (e.g., Salary)
    - Enter an amount:
      - Positive → Income (e.g., 5000)
      - Negative → Expense (e.g., -1200)

4.  View your:
    - Total balance
    - Total income
    - Total expenses

5.  Delete a transaction:
    - Hover over it
    - Click the **x** button

## Key Concepts

- **LocalStorage** for saving transactions
- **DOM manipulation** for real-time updates
- **Array methods** to manage transaction data
- **Intl.NumberFormat** for formatting currency

## Future Improvements

- Add categories (Food, Rent, etc.)
- Filter or search transactions
- Monthly reports and charts
- Export data (CSV or PDF)

## Author

Built as a project to practice **state management**, **DOM updates**, and **local data persistence** using JavaScript.
