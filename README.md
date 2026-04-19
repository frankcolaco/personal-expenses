This is an app that helps tracks expense. 
Currently it is a standalone app which is under testing and under development.

**Version 1.1**
✨ New Features
1️⃣ Categories + Subcategories

Settings → Manage categories opens a modal to view all categories
Pre-built categories: Personal, Home, Food, Transport, Health, Other (expenses) and Salary, Freelance, Other (income)
Each category has subcategories (e.g., Home → Rent, Utilities, Groceries)
When you select a category with subcategories in the Add form, a second dropdown appears for the subcategory
Add custom categories with the "+ Manage categories" button
Delete custom categories anytime

2️⃣ CSV Import

History tab → Import button lets you upload a CSV file
Import format (8 columns):

  Date, Type, Category, Subcategory, Person, Amount, Note, Tag, Currency
  2024-01-15, expense, Food, Groceries, Rahul, 500, Weekly shopping, weekly, INR

Bulk-adds transactions to your existing data
Perfect for migrating from spreadsheets or other apps

3️⃣ Edit Existing Expenses

Click any transaction in History to open the edit modal
Change date, amount, category, subcategory, or note
Delete the transaction from the same modal
All changes save instantly

4️⃣ Income Tracking

Add page now has Income/Expense toggle at the top
Track both earnings and expenses separately
Dashboard shows:

Expenses (red)
Income (green)
Net flow (income − expenses)


History filter shows "All", "💸 Expenses", or "💰 Income"
Analysis breaks down both income and expenses per period
Export CSV includes a "Type" column for each transaction


📊 Updated Dashboard

4 metrics: Expenses | Income | Net | Budget used
Expenses breakdown by category (bar or pie)
Recent transactions show both income (+) and expenses

📁 Export/Import CSV Example
When you export, you get a file like:
`Date,Type,Category,Subcategory,Person,Amount,Note,Tag,Currency
2024-01-20,expense,Food,Groceries,Rahul,800,Weekly shopping,,INR
2024-01-21,income,Salary,Base,Rahul,50000,January salary,,INR`


**Version 1:**
✨ **Features included**

1. Dashboard with Month / Quarter / Year toggle
2. Budget tracker with % alert (set in Settings)
3. Spending breakdown by category and person (bar charts)
4. Full history with search + category filter
5. Monthly, quarterly, and yearly analysis view
6. People manager with autocomplete
7. Recurring expense & custom tag fields
8. One-tap CSV export (open in Google Sheets / Excel)
9. All data saved locally on the device (no server needed)
