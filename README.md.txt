Automated Attendance Tracker (Google Apps Script) :
An automated attendance management system built using Google Apps Script and Google Sheets. The script calculates each student's attendance percentage and automatically sends warning emails to students whose attendance falls below the required threshold of 75%. It also updates the attendance status in the spreadsheet, reducing manual effort and improving efficiency.

Features :
• Automatically reads student attendance data from Google Sheets
• Calculates attendance percentage for each student
• Identifies students with attendance below 75%
• Sends automated warning emails using MailApp/GmailApp
• Updates the Status column as OK or Alert Sent
• Supports automatic execution using time-based triggers

Workflow :
1. Read student details from the Google Sheet.
2. Calculate attendance percentage using the formula:
   Attendance % = (Attended Classes ÷ Total Classes) × 100
3. Compare the calculated attendance with the 75% threshold.
4. Send a warning email if the attendance is below 75%.
5. Update the Status column in the sheet.
6. Repeat the process for all student records.

Technology Stack :
• Google Apps Script (JavaScript)
• Google Sheets
• MailApp / GmailApp

Google Sheet Structure :
Roll No. | Name | Email | Total Classes | Attended Classes | Attendance % | Status

Installation :
1. Create a Google Sheet with the required columns.
2. Open Extensions → Apps Script.
3. Paste the project code into Code.gs.
4. Save the script.
5. Run the function once and grant the required permissions.
6. Create a time-based trigger to automate attendance checking.

Screenshots :
The screenshots folder contains-
• Google Sheet interface
• Sample warning email
• Apps Script editor

Author :
Pranjali Gavane (CD24032)
Developed as part of the Value Added Course on Agentic AI & Automation.
