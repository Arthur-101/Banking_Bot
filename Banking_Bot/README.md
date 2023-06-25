#                       Python Banking System Documentation


# ->  Table of Contents:

1. Introduction
2. Project Overview
3. Requirements
4. Installation
5. Usage
6. Functionality
7. File Structure
8. Dependencies
9. Contributors
10. Conclusion


#   1. INTRODUCTION
This documentation provides an overview and instructions for a Python-based banking system project. The project aims to simulate basic banking operations such as user registration, login, account management, deposit, withdrawal, and loan operations. Additionally, the system includes an employee login functionality to view customer information without making any changes.


#    2. PROJECT OVERVIEW
The Python banking system project offers a graphical user interface (GUI) implemented using the `customtkinter` module. The system utilizes several Python libraries and modules, including `csv`, `string`, `random`, `pyttsx3`, `PIL`, `playsound`, `datetime`, and `time`. The project comprises three main windows with different functionalities and themes: the initial greeting window, the user interface window with customer and employee tabs, and the customer/employee information window.


#     3. REQUIREMENTS
To run the Python banking system project, the following requirements must be met:

-Python 3.x installed on the system.
-Required Python modules: `csv`, `string`, `random`, `pyttsx3`, `PIL`, `playsound`, `datetime`, `time`, and `customtkinter`.


#      4. INSTALLATION
To install the Python banking system project, follow these steps:

1. Ensure Python 3.10 is installed on your system. If not, download and install it from the official Python website (https://www.python.org).

2. Download the project files and save them to a directory of your choice.

3. Open a terminal or command prompt and navigate to the project directory.

4. Install the required Python modules by running the following command:
    pip install string random datetime time pyttsx3 PIL playsound customtkinter

5. Once the dependencies are installed, you are ready to run the project.


#      5. USAGE
To use the Python banking system project, follow these steps:

1. Open a terminal or command prompt and navigate to the project directory.

2. Run the project using the following command:
    python main.py
            OR
1. Open VS Code and navigate to the project directory.

2. Open the `Banking_system.py` file in VS Code and run it.

3. The project will display a window with a greeting message and various options. Enter commands in the "Enter Command" section to interact with the program, ask for the time, date, or greet the program.

4. Click the "Start" button to proceed to the main user interface window.

5. In the user interface window, you can choose between the light and dark themes using the "Theme" option in the bottom left corner.

6. The user interface window consists of a tab view widget with two tabs: "Customer" and "Employee." The "Customer" tab allows customers to register or log in, while the "Employee" tab is for employee login.

7. To register as a customer, click the "Register" button in the "Customer" tab. A new window will appear, prompting you to enter your desired username, password, confirmation password, and Gmail address.

8. After entering the registration details, click the "Done" button. If all inputs are valid, your registration will be successful, and your information will be saved in a CSV file.

9. Customers can then log in to their accounts by entering their username and password in the "Login" section of the "Customer" tab.

10. In the "Employee" tab, registered employees can log in to view customer information. Enter the employee's username and password in the "Login" section.

11. After successfully logging in as either a customer or an employee, the window will transition to a new window with the customer/employee information.

12. In the customer/employee information window, you can use the "Theme" option in the bottom left corner to switch between light and dark themes.

13. The window displays customer/employee information, and three buttons are available: "Main" to return to the first window, "Back" to return to the second window, and "Exit" to close the program.


#      6. FUNCTIONILITY
The Python banking system project provides the following functionalities:

1. Greeting window: Displays a welcome message and allows users to enter commands, ask for the time or date, and change the program's theme.

2. User interface window: Offers a tab view with "Customer" and "Employee" tabs. Customers can register or log in, while employees can log in to view customer information. The window provides options to change the theme, return to the first window, or exit the program.

3. Customer registration: Allows customers to register by entering a username, password, confirmation password, and Gmail address. Asks to enter initial amount and to clear a captcha. After successful registration, customer information is saved in a CSV file.

4. Customer login: Enables customers to log in using their username and password. Upon successful login, the program transitions to the customer information window.

5. Employee login: Allows registered employees to log in using their username and password. After successful login, the program transitions to the employee information window.

6. Customer/employee information window: Displays customer or employee information and provides options to change the theme, return to the first or second window, or exit the program.

#      7. FILE STRUCTURE
The Python banking system project includes the following files:
1. Banking_system.py : This is the primary script that runs when you start. The main entry point of the program. Contains all the functions and logic for the project.

2. `Files`: Directory containing `Items` folder and CSV files for storing customer information.

3. `Items`: Directory containing all the button images and sound tracks.


#      8. DEPENDENCIES
The Python banking system project relies on the following Python modules:

1. `csv`: Required for reading and writing customer information in CSV files.
2. `string`: Used for string operations and manipulations.
3. `random`: Utilized for generating random values such as captchas.
4. `pyttsx3`: Provides text-to-speech functionality.
5. `PIL`: Required for image processing and manipulation.
6. `playsound`: Enables playing sound files.
7. `datetime`: Used for date and time operations.
8. `time`: Required for time-related operations.
9. `customtkinter`: Implements the custom GUI framework used in the project.

#      9. CONTRIBUTORS
The Python banking system project was developed by [Saurav] as a school project.

#      10. CONCLUSION
This documentation provides an overview of the Python banking system project, including its functionalities, requirements, installation instructions, and usage guidelines. By following these instructions, you should be able to run and interact with the program successfully.
