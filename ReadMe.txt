Ambient Assistance Living Application
This project is an Ambient Assistance Living Application that analyses ambient conditions (temperature, gas, CO, etc.), as well as biosignals (temperature, blood pressure) of a certain user. The user can have several illnesses, and the system manages 10 possible diseases. The bot stores all input data and rules in CSV files. The application is interactive, and the user can interact with the bot using a graphical user interface, as in a chat, as well as based on voice. The bot can analyze daily, weekly, monthly, and yearly data. It can also generate reports and graphics based on the collected input.

Installation and Setup
Clone the repository to your local machine.
Install the required packages using pip install -r requirements.txt.
Create a MySQL database named "healthbot" and run the SQL script provided in the "sql" folder to create the tables required for the application.
Modify the database connection settings in the healthbot.py file to match your local environment.
Run the healthbot.py file to start the application.

Usage
The application will present a menu with several options:
Check environment and patient status
Show all patients
Show data based on: day, week, month, year
Exit
Select an option from the menu by typing its number and pressing enter.
If you selected the "Check environment and patient status" option, the application will display the current environment and patient status.
If you selected the "Show all patients" option, the application will display all the patients in the system.
If you selected the "Show data based on: day, week, month, year" option, the application will ask you to select the time interval you want to display data for (day, week, month, or year). After you select the interval, the application will display the environment and patient data for that interval.
To exit the application, select the "Exit" option from the menu.


Testing
To test the application, run the test_healthbot.py file. This file contains unit tests for each of the application's functions. The tests can be run using the pytest package.

Memory Management
The application implements CPU scheduling to calculate process time based on the bot's various functionalities. This helps manage the bot's memory usage and ensures that the application is responsive and efficient.