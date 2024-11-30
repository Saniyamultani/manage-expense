Expense Tracker App:
The Expense Tracker App allows users to manage their daily expenses by adding, categorizing, and visualizing their spending data.

Features

1. Add Expense
   - Users can add expenses with details such as:
     - Category: Select from predefined options (`Food & Beverage`, `Rent`, `Transport`, `Relaxing`).
     - Amount: Enter the expense amount.
     - Date: Select the date of the expense.

2. Expense List
   - Displays a table containing:
     - Category, Amount,Date, and a Delete Button to remove entries.

3. Total Amount Calculation
   - Automatically updates and displays the total sum of all expenses.

4. Visualization
   - A pie chart displays the distribution of expenses by category, providing an overview of spending patterns.


Project Structure

HTML
- Provides the structure of the app, including input fields, a table to display expenses, and a canvas for the pie chart.
 CSS
- Ensures the application is visually appealing with:
  - A responsive design for different screen sizes.
  - Styling for buttons, input fields, and the table.

JavaScript
- Implements the core functionality, such as:
  - Adding, deleting, and updating expenses.
  - Dynamically updating the total amount.
  - Integrating a Chart.js pie chart for data visualization.

Setup and Usage

Prerequisites
- A modern web browser.
- Internet connection to fetch the `Chart.js` library.

Steps
1. Open the App:
   - Save the code into a `.html` file and open it in your browser.

2. Add Expense:
   - Select a category, input the amount, choose a date, and click Add.

3. View and Manage Expenses:
   - Expenses will appear in the table below the input section.
   - To remove an expense, click the Delete button next to it.

4. Visualize Spending:
   - The pie chart will dynamically update to reflect the distribution of spending by category.


Dependencies

- [Chart.js](https://www.chartjs.org/) (loaded via CDN):
  - A JavaScript library for creating charts, used here for the pie chart visualization.

---

File Structure

- HTML:
  - Defines the layout, input fields, table, and chart container.
- CSS:
  - Styles the app with responsive and user-friendly design.
- JavaScript:
  - Manages the logic for adding expenses, updating the table, and rendering the chart.

Improvements and Next Steps

1. Validation Enhancements:
   - Add more robust validation for inputs.
   
2. Persistent Storage:
   - Save expenses to local storage or a database for future access.

3. Enhanced Visualization:
   - Add bar charts or trend analysis for expenses over time.

4. Additional Features:
   - Include more categories or allow custom category creation.

Screenshots

1. Expense Input Section:
   - A clean interface for entering new expenses.
2. Expense Table:
   - Lists all expenses with options to delete individual entries.
3. Pie Chart:
   - Provides an at-a-glance view of spending habits.

License

This project is open-source and available for customization and improvement. 
