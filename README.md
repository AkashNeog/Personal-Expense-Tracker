# Personal-Expense-Tracker https://akashneog.github.io/Personal-Expense-Tracker/
Personal Expense Tracker
This is a simple and interactive Personal Expense Tracker web application built with HTML, CSS, JavaScript, and Chart.js. The app allows users to track their daily expenses, filter data by categories and dates, visualize expenses, and export data to CSV format. Additionally, a dark mode feature is included.

Features Implemented:

Expense Tracking:
Users can add expenses with a category, amount, and date.
Expenses are displayed in a table format, showing the category, amount, and date.

Local Storage:
Expenses are stored in the browser's local storage, so the data persists even after the page is refreshed or closed.

Total Amount:
The total expense amount is automatically calculated and displayed at the bottom of the table.

Expense Filters:
Users can filter expenses by category and date using dropdown menus and a date picker.
The "Clear Filters" button removes any applied filters and resets the table.

Chart Visualization:
A pie chart is used to visualize expenses based on categories.
The chart updates dynamically as expenses are added, deleted, or filtered.

Delete Expenses:
Each expense entry has a delete button that removes it from the table and updates the data in local storage.

Clear All Expenses:
A "Clear All" button allows users to delete all expenses in one click after a confirmation prompt.

Download Expenses as CSV:
Users can download the list of expenses in CSV format by clicking the "Download CSV" button.

Dark Mode:
Users can toggle dark mode using a button to change the background and text colors for a better viewing experience in low-light conditions.

Responsive Design:
The app is designed to be responsive using Bootstrap, ensuring it works well on both mobile and desktop devices.

How it Works:

Adding Expenses:
Select a category from the dropdown, enter the amount, and choose a date. Then click the "Add" button to save the expense.

Viewing Expenses:
Expenses are listed in a table format. The total amount spent is updated automatically.

Filtering Expenses:
Filter by category and/or date to narrow down the expenses shown in the table.

Expense Breakdown:
A pie chart shows the distribution of expenses by category for better visualization.

Delete & Clear Expenses:
Delete individual expenses or clear all expenses at once.

Exporting Data:
Download your expenses as a CSV file by clicking the "Download CSV" button.

Technologies Used:

HTML5: Markup language for structuring the app.

CSS3: Styling the app, including custom dark mode support.

Bootstrap: Framework for responsive design.

JavaScript: For dynamic behavior, such as adding/deleting expenses, filtering, and updating the chart.

Chart.js: To visualize expenses in a pie chart format.

jQuery: For DOM manipulation and event handling.
