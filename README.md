# Simple Loan-Calculator Using Java Script

# Sample Images
<img width="487" alt="Screenshot 2023-11-11 034845" src="https://github.com/ViNu-23/Loan-Calculator/assets/59360964/a276d052-7536-49df-bc4b-69ea069cacd7">
<img width="428" alt="Screenshot 2023-11-11 034912" src="https://github.com/ViNu-23/Loan-Calculator/assets/59360964/228d312d-28a6-4653-a0b1-02c54bced7e4">

# Application Usage:
Users input loan details (amount, interest rate, and duration).
Upon submission, the application calculates and displays the monthly payment, total loan amount, and total interest.
If there's an error in the input, an alert is displayed for a brief period.
Ensure that the HTML structure and JavaScript code are properly integrated into your web page for the application to work as intended.

# JavaScript Code:

Form Submission Event Listener:

The script targets the form with the ID "loan-form" and adds a submit event listener that calls the calculate function.
calculate Function:

This function is executed when the form is submitted.
It retrieves values from the input fields (loan amount, interest rate, and loan duration) and performs a loan calculation.
The calculated results are displayed in the "results" div.
If the input values are not valid (e.g., not numeric), an error message is displayed.
showAlert Function:

This function creates a dynamically generated alert div to display error messages.
It inserts the error div into the HTML, specifically before the heading in the card.
Timeout Function:

There's a setTimeout function that attempts to remove the alert message after 3 seconds. However, there is an issue with the code.

# Calculate Your Loan
 https://vinu-23.github.io/Loan-Calculator/