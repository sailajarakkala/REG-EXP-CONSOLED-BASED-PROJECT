 REG-EXP-CONSOLED-BASED-PROJECT
Sure! Here's a more detailed and enriched version of the project description that includes objectives, technologies used, and potential enhancements. You can use this as a section above or within your README file:

Project Description

This Regular Expression-Based Console Project is a simple yet practical demonstration of how regular expressions can be utilized for user input validation and formatting in Python. The script is designed to interact with users through the command line interface and ensures that all provided information adheres to specific formats.

 🧠 Key Functionalities

1. Name Validation
   Accepts alphabetic characters and spaces only.
    Prevents input of numbers, special characters, or empty fields.

2. Date of Birth (DOB) Validation
   Requires the format dd-mm-yyyy.
    Upon successful validation, it converts the numeric month to a three-letter abbreviation (e.g., 01 → jan).

3. Email Validation
    Restricts input to lowercase Gmail addresses only (e.g., john123@gmail.com).
    Ensures basic email structure using regex.

4. Mobile Number Validation
    Requires the format xxx-xxx-xxxx.
    Converts and stores it as a continuous 10-digit number without dashes.

5. Formatted Output
   Displays all collected and formatted data back to the user in a clean, user-friendly way.

 🔧 Technologies Used

Python 3
re Module (Regular Expressions)
Standard Input/Output (Console Interaction)

💡 Learning Objectives
 Understand and implement regex for data validation.
 Handle user inputs in an interactive CLI.
 Format and transform input data after validation.
 Improve string manipulation and pattern matching skills.

 🚀 Potential Enhancements
 Avalidation for additional fields (e.g., address, pin code).
 Extend email support to other domains (e.g., yahoo, outlook, etc.).
 Allow international phone number formats.
 Integrate a GUI (e.g., using Tkinter or PyQt).
 Export collected data to a CSV or JSON file.

