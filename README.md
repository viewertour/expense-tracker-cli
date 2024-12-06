# expense-tracker-cli
Description：Expense Tracker" is a beginner-friendly open-source tool for managing personal and business finances. As a new user myself, I can attest to its simplicity and effectiveness. With this free tool, you can track your expenses, monitor your income, and set budgets with ease. Plus, because it's open-source, the community is actively working to improve it, adding new features and fixing issues regularly. If you're new to financial management or simply looking for a user-friendly solution, give Expense Tracker a try!
In this tool：
Users can add an expense with a description and amount.
Users can update an expense.
Users can delete an expense.
Users can view all expenses.
Users can view a summary of all expenses.
Users can view a summary of expenses for a specific month (of current year).


git clone https://github.com/siamonas/expense-tracker-cli.git
cd expense-tracker-cli
python -m venv venv

# On Windows:
.\venv\Scripts\activate

# On macOS and Linux:
source venv/bin/activate

pip install -r requirements.txt

python expense-tracker-cli -h # Show help
python expense-tracker add --description "Lunch" --amount 20 # Add an expense
python expense-tracker add --description "Dinner" --amount 10 # Add another expense
python expense-tracker list # List all expenses 
python expense-tracker summary # Show summary of expenses
python expense-teacker summary --month 8 # Show summary of expenses for specific month
python expense-tracker delete --id 1 # Delete an expense by ID
