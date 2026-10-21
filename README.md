
# Week 2 Assignment: Budget Tracker

## Project Description

My Budget Tracker is a simple web page built using HTML and CSS.
It helps users understand how to organize and track their daily expenses.

This project builds on the Budget Tracker created in Week 1 by adding
an expense table, an improved expense form, multimedia content,
interactive HTML elements, and advanced CSS selectors.

## Features

### 1. Expense Table
- Displays sample expense records.
- Uses `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>`.
- Includes Name, Amount, Category, and Date columns.
- Contains five sample expenses.
- Uses alternating row colors and a hover effect.

### 2. Add Expense Form
- Includes an expense name input.
- Includes an amount input.
- Includes a category dropdown with Food, Transport, Rent,
  Entertainment, and Other.
- Includes a date input.
- Uses labels connected to their inputs through matching IDs.
- Includes an Add Expense button.

The form is a front-end demonstration. Adding and saving expenses
will be implemented in a future JavaScript lesson.

### 3. Multimedia Content
- Displays a logo using the HTML `<img>` element.
- Embeds a YouTube video using the `<iframe>` element.

### 4. Interactive HTML Elements
- Uses `<details>` and `<summary>` to create collapsible instructions.
- Changes the table row background color when the mouse hovers over it.
- Changes the button background color when hovered.
- Uses a pointer cursor on the button.

### 5. Advanced CSS Selectors
The project uses the following advanced CSS selectors:

- Descendant selector: `.expenses-section th`
- Direct child selector: `.add-expense-section > h2`
- Position pseudo-class: `tr:nth-child(even)`
- Negation pseudo-class: `input:not([type="submit"])`
- Focus pseudo-class: `input:focus`
- Hover pseudo-class: `tr:hover`

## Technologies Used

- HTML5
- CSS3

## Project Files

- `index.html` - Contains the structure and content of the web page.
- `style.css` - Contains the page layout, colors, form styling,
  table styling, responsive design, and advanced selectors.
- `README.md` - Explains the project, features, and technologies used.

## How to Run the Project

1. Download or clone the project repository.
2. Make sure all three files are in the same project folder.
3. Open `index.html` in a web browser.
4. Connect to the internet to load the logo and YouTube video.

## Future Improvements

JavaScript can be added to make the form functional, calculate total
expenses, and save expense records.

## Author

Student
