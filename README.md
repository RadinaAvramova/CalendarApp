# Calendar Project 
Welcome to the Calendar Project! This project is a command-line calendar application implemented in C. It allows users to perform various operations such as finding out the day for a given date, printing all the days of a month, and adding notes to specific dates. This README will provide an overview of the project, its features, and instructions for usage.

## Features
The Calendar Project offers the following features:

1 **Find Out the Day:** Users can input a date (day, month, and year) and find out the corresponding day of the week.

2. **Print all the Days of a Month:** Users can input a month and a year, and the application will display a calendar for that month, showing all the days with their corresponding days of the week.

3. **Add Note:** Users can add notes to specific dates, providing a brief description of events, tasks, or reminders for that day.

## Installation and Usage
To use the Calendar Project, follow these steps:

1. **Download the Source Code:** Download the provided source code files (calendar.c) to your computer.

2. **Compile the Code:** Compile the source code using a C compiler. For example, if you're using GCC, you can compile the code with the following command in your terminal or command prompt:
gcc calendar.c -o calendar

3. **Run the Application:** After compiling the code successfully, you can run the application by executing the generated executable file. For example:
./calendar

4. **Interact with the Application:** Once the application is running, you'll be presented with a menu of options. Follow the prompts to perform the desired operation:

To find out the day for a specific date, choose option 1 and input the date in the format (DD MM YYYY).

To print all the days of a specific month, choose option 2 and input the month and year (MM YYYY). You can navigate between months using 'n' for next and 'p' for previous. Additionally, you can press 's' to view notes added for that month.

To add a note to a specific date, choose option 3 and follow the prompts to input the date and note.

5. **Exit the Application:**  You can exit the application at any time by choosing option 4 from the menu.

Notes
The application provides a simple command-line interface for interacting with the calendar functionalities. It's designed for ease of use and quick access to important date-related information.

The calendar functionality includes support for leap years and adjusts the days of the month accordingly.

Notes added to specific dates are stored persistently using file I/O operations. This allows users to retrieve their notes even after closing and reopening the application.
