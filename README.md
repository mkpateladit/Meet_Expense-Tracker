# Meet_Expense-Tracker
📊 Expense Tracker Application

A Java Swing-based desktop application to track personal expenses with budgeting features, transaction history, and detailed reporting.

✨ Key Features
Intuitive GUI: Clean, user-friendly interface with modern styling

Expense Categories: Track expenses in predefined categories (Food, Travel)

Transaction Types: Supports both Credit and Debit transactions

Payment Methods: Records payment method (Cash, Card, UPI)

Budget Monitoring: Alerts when category budgets are exceeded

Detailed Reporting: Generates comprehensive expense reports

Data Persistence: Saves transactions to text files

Thread-Safe Operations: Uses synchronized collections for thread safety

Responsive Design: Adapts to different screen sizes

🛠️ Technical Implementation

Core Java: Built using Java 8+ features

Swing GUI: Modern UI with JFrame, JPanels, and Swing components

File I/O: Saves data to expenses.txt and report.txt

Date Handling: Uses Java 8's LocalDate for date operations

Design Patterns: Implements abstract classes and inheritance

Thread Safety: Uses synchronized collections for concurrent access

📋 Usage Instructions

Enter expense details:

Description (e.g., "Dinner at restaurant")

Amount (positive number)

Category (Food/Travel)

Type (Credit/Debit)

Action (Cash/Card/UPI)

Click "Add Expense" to log the transaction

Use "Generate Report" to view spending summaries

"Clear All" resets all transactions

📊 Budget Management

Default budgets:

Food: ₹1000

Travel: ₹2000

Application warns when category budgets are exceeded

📁 File Outputs

expenses.txt: Logs all transactions in readable format

report.txt: Saves generated reports for future reference

🚀 How to Run

Ensure Java 8+ is installed

Compile and run ExpenseTracker.java

Or execute the JAR file if available

📝 Future Enhancements

Add more expense categories

Implement monthly budget tracking

Add data visualization (charts/graphs)

Support for database storage

Export reports in PDF/Excel formats

🖥️ Running the Application
Method 1: Running from Source Code (IDE or Command Line)
Clone the repository (if applicable):

bash
Copy
git clone <your-repository-url>
cd <project-folder>
Compile the Java file:

bash
Copy
javac ExpenseTracker.java
Run the application:

bash
Copy
java ExpenseTracker
Method 2: Running a Pre-Built JAR (If Available)
Download the .jar file (if provided in releases).

Run via command line:

bash
Copy
java -jar ExpenseTracker.jar

Screenshots: 
![image alt]()


Technical Documentation :

Class Diagram :
![image alt](https://github.com/mkpateladit/Meet_Expense-Tracker/blob/main/Screenshot%202025-04-13%20101528.png?raw=true)
 
Sequence Diagram :
![image alt](https://github.com/mkpateladit/Meet_Expense-Tracker/blob/main/Screenshot%202025-04-13%20220108.png?raw=true)

Flow Diagram :

![image alt](https://github.com/mkpateladit/Meet_Expense-Tracker/blob/main/Screenshot%202025-04-13%20215749.png?raw=true)
