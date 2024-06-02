Money Tracker App
The Money Tracker App is a simple web application that allows users to track their expenses and income. Users can input transactions specifying the category, amount, description, and date. The app displays a list of transactions and calculates the total balance.

Features
Add expenses and income with details.
View a list of all transactions.
Delete transactions from the list.
Calculate the total balance based on income and expenses.
Technologies Used
HTML, CSS, JavaScript for the frontend.
Node.js, Express, and MongoDB for the backend.

Usage
Add a Transaction:

Select a category (Expense or Income).
Enter the amount.
Provide a brief description in the "Info" field.
Select the date of the transaction.
Click the "Add" button.
View Transactions:

The added transactions will appear in the table below the form.
The total balance will be updated accordingly.
Delete a Transaction:

Click the "Delete" button next to any transaction to remove it from the list.
The total balance will be recalculated.
Code Overview
Frontend
HTML Structure:

The main HTML file (index.html) contains a form for inputting transactions and a table for displaying them.

CSS Styling:

The CSS file (style.css) includes styling for the layout, form, table, and buttons.

JavaScript Functionality:

The JavaScript file (script.js) handles form submissions, updating the table, calculating the total balance, and deleting transactions.

Backend
Server Setup:

The server is set up using Express (app.js). It includes routes for handling form submissions and serves the static HTML file.

Database Connection:

MongoDB is used to store transaction data. The connection to the MongoDB database is established using Mongoose.
