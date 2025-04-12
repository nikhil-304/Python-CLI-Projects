# 💸 Personal Finance Tracker (CLI Tool)

A Command Line Interface tool written in Python to help you track your income and expenses, view detailed summaries, and visualize financial trends over time with graphs.

## 📌 Features
- Add transactions with custom or today’s date
- Specify amount, category (Income/Expense), and description
- View transactions between any two dates
- Plot income vs expense graph over time
- Calculates total income, total expense, and net savings
- Stores all data in a local CSV file

## 🛠 Tech Stack
- Language: Python 3
- Libraries: pandas, csv, matplotlib, datetime
- Data Storage: CSV file (finance_data.csv)

## 📦 Installation
Clone the Repository:
git clone https://github.com/nikhil-304/Python-CLI-Projects.git
cd Python-CLI-Projects/Personal\ Finance\ Tracker

Install Dependencies:
pip install pandas matplotlib

## 🚀 How to Use
Run the program:
python main.py

You'll see three options:
1. Add a new transaction
2. View transactions and summary within a date range
3. Exit

Add a Transaction:
- Enter date (dd-mm-yyyy) or leave blank for today
- Enter amount
- Choose category: Income or Expense
- Add description

View Transactions:
- Enter start and end date in dd-mm-yyyy format
- View filtered transactions
- See total income, expense, and net savings
- Optionally, plot the graph

Plot Graph:
- Shows a line chart of Income (green) and Expense (red) over time

## 🧠 Future Enhancements
- Monthly/yearly reports
- Pie chart for category-wise spending
- Password protection
- Export to Excel or PDF

## 🙌 Author
Nikhil Shrivastava  
GitHub: https://github.com/nikhil-304

## 📄 License
This project is licensed under the MIT License.
