# Budget-Tracker
This is a simple budget tracker application built using HTML, CSS, and JavaScript. It allows users to track their income, expenses, and overall financial health. The application enables users to input and manage their transactions, upload receipts (images or PDFs), and view a summary of their financial status.
Features

    Transaction Management: Add, view, and delete transactions with details like description, amount, category, and date.
    Receipt Upload: Upload receipts in image or PDF format and extract transaction details using OCR (Tesseract.js).
    Financial Summary: Displays total income, total expenses, and balance.
    Budget Health Status: Provides visual feedback on your budget’s health (healthy, warning, or in danger).
    Download and Print: Option to download the transaction data as an Excel file or print the current view.

Technologies Used

    HTML5: For structure and layout.
    CSS3: For styling and responsiveness.
    JavaScript: For interactivity and logic (using libraries like Tesseract.js, pdf.js, and xlsx.js).
    Tesseract.js: For Optical Character Recognition (OCR) to extract text from images and PDFs.
    pdf.js: For processing PDF files and extracting text.
    XLSX.js: For exporting transaction data as an Excel file.

Setup

    Clone the repository to your local machine:

    git clone https://github.com/yourusername/budget-tracker.git

    Open the index.html file in your preferred browser to run the application.

Usage

    Add Transaction: Fill in the form with the description, amount, category, and date of the transaction.
    Upload Receipt: Upload an image or PDF receipt to automatically fill in the transaction details using OCR.
    Transaction History: View the list of transactions and delete any unwanted records.
    Download as Excel: Click the "Download as Excel" button to export your transaction data.
    Print: Use the "Print" button to print the transaction summary.

File Upload

    The app supports file uploads for receipts in image (JPEG, PNG, etc.) or PDF format. The text from these files will be automatically extracted and populated in the form.

Budget Health

    Healthy Budget: If your balance is positive, the app will show a green message encouraging you to keep up the good work.
    Warning Zone: If your balance is negative but within an acceptable range, a yellow warning will be shown, advising you to adjust your spending or increase income.
    Danger Zone: If your balance is deeply negative, a red danger message will alert you to reduce spending.

Example of Usage
Adding a Transaction:

    Description: "Grocery"
    Amount: 500
    Category: "Groceries"
    Date: 2024-12-19

Budget Health Status:

    Total Income: 2000
    Total Expenses: 1500
    Balance: 500 (Healthy)

Contributions

Feel free to fork the repository and submit pull requests if you have improvements or fixes in mind.
