# Bankist App

![image](https://github.com/user-attachments/assets/8dc66129-e22f-4050-85f4-f4b6058faa26)

## Table of Contents

1. [Overview](#overview)
2. [Demo](#demo)
3. [Features](#features)
   - [Recent Updates](#recent-updates)
4. [Technologies Used](#technologies-used)
5. [Disclaimer](#disclaimer)
6. [Getting Started](#getting-started)
7. [Usage](#usage)
8. [Contribution](#contribution)
9. [Further Reading](#further-reading)
10. [Acknowledgements](#acknowledgements)

## Overview

The Bankist app is a simple web-based banking application that allows users to log in, view their account balance, transfer money, request loans, and close accounts. This project was built as part of Jonas Schmedtmann's JavaScript course and showcases various features including data manipulation, user authentication, and UI updates.

## Demo

Check out the live demo of the site [Bankist App](https://bankist-alahmady.netlify.app/)

## Features

- **Login**: Users can log in with their username and PIN.
- **Balance Overview**: Displays the current balance of the logged-in account.
- **Movements**: Shows deposits and withdrawals in a transaction history.
- **Summary**: Provides a summary of income, expenses, and interest.
- **Money Transfer**: Allows users to transfer money between accounts.
- **Loan Request**: Users can request loans if they meet certain criteria.
- **Account Closure**: Option to close the account if the username and PIN match.
- **Sorting**: Option to sort transactions by date.

### Recent Updates

- **Bankist App Data & Features Update**:
  - Updated the app to include new account data with movement dates, currencies, and locales for a more realistic banking experience.
  - Refactored the code responsible for the display and calculation of movements, balances, and summaries to accommodate these changes.
  - Implemented features such as formatted date display using `Intl.DateTimeFormat()` and currency formatting with `Intl.NumberFormat()`, improving the app's localization.

## Technologies Used

- **HTML**: Structure and layout of the application.
- **CSS**: Styling and visual presentation.
- **JavaScript**: Interactive features and logic.

## Disclaimer

The HTML and CSS code in this project were originally written by Jonas Schmedtmann as part of his course materials. The JavaScript code and some small edits to the HTML and CSS have been made by me to enhance the functionality and adapt it to my learning objectives.

## Getting Started

1. **Clone the Repository**:
   git clone https://github.com/Ahmad-Al-Ahmady/bankist-app.git

2. **Navigate to the Project Directory**:
   cd bankist-app

3. **Open index.html in Your Browser**:
   You can open the index.html file directly in your browser to view the application.

## Usage

1. **Log In**: Enter a predefined username and PIN to access the account. For example:

   - Username: `js`
   - PIN: `1111`

2. **View Balance**: After logging in, your current account balance will be displayed on the screen.

3. **Transfer Money**:

   - Enter the recipient’s username in the "Transfer to" field.
   - Input the amount you wish to transfer in the "Amount" field.
   - Click the "Transfer" button to complete the transaction.

4. **Request Loan**:

   - Enter the desired loan amount in the "Amount" field.
   - Click the "Request Loan" button to submit your loan request. Loans will only be granted if certain conditions are met, such as having a sufficient account balance.

5. **Close Account**:

   - Enter your username and PIN in the "Confirm user" and "Confirm PIN" fields.
   - Click the "Close Account" button to delete your account. This action is irreversible.

6. **Sort Transactions**:
   - Click the "SORT" button to toggle between sorting transactions by amount or displaying them in their original order.

## Contribution

If you’d like to contribute to this project, feel free to submit a pull request or open an issue.

## Further Reading

- [Jonas Schmedtmann's JavaScript Course](https://www.udemy.com/course/the-complete-javascript-course/)

## Acknowledgements

Special thanks to [Jonas Schmedtmann](https://github.com/jonasschmedtmann) for this project's course materials and inspiration.
