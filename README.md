# FILE-MANAGEMENT-TOOL-_1

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: MOHAMMAD MUSTAFA KARAM KHALID

**INTERN ID**: CT08GIX

**DOMAIN NAME**: C++ PROGRAMMING

**BATCH DURATION**: December 25th, 2024 to January 25th, 2025.

**MENTOR NAME**: NEELA SANTHOSH

# DESCRIPTION: This project is a C++ application designed to showcase file-handling techniques using the <fstream> library. The program provides a user-friendly, menu-driven interface that allows users to perform three essential operations on a text file: write, append, and read. By implementing these functionalities, the project demonstrates the practical use of files for storing and managing data in persistent storage.

Overview of File Handling
File handling is a crucial aspect of programming that enables applications to store data beyond the runtime of a program. Unlike in-memory variables, files provide a means to store, retrieve, and manage data persistently. This project focuses on text files and uses the <fstream> library, which provides classes like ofstream, ifstream, and fstream for writing, reading, and both operations combined. The program leverages these classes to handle various file operations efficiently and interactively.

Key Features
Write to File:

Purpose: Allows users to write data to the file. Any existing data in the file is overwritten.
Implementation: The writeToFile() function opens the file in write mode using std::ofstream. It prompts the user for input, writes the provided data to the file, and then closes the file.
Use Case: Ideal for creating a new file or resetting the content of an existing file.
Append to File:

Purpose: Enables users to add new data to the file without modifying or deleting existing content.
Implementation: The appendToFile() function opens the file in append mode using std::ofstream with the std::ios::app flag. User input is appended to the file, ensuring that previous data remains intact.
Use Case: Useful for adding logs, new records, or appending information to reports.
Read from File:

Purpose: Displays the contents of the file to the user, line by line.
Implementation: The readFromFile() function uses std::ifstream to open the file in read mode. It reads the file line by line using std::getline() and displays the content on the console.
Use Case: Allows users to verify the data stored in the file or retrieve stored information.
Menu-Driven Interface:

The program offers a simple and intuitive menu that lets users choose between writing, appending, reading, or exiting the application.
The menu ensures ease of navigation and allows users to perform multiple operations sequentially without restarting the program.

#OUTPUT OF THE TASK: 

PASTE LINK FROM NEW ISSUE 
