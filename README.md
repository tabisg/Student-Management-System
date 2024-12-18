# Student-Management-System
# Student Management System

The **Student Management System** is a simple Python program that allows users to manage a list of students. It provides options to view, add, search, and remove student records. This script is interactive, user-friendly, and provides error handling for invalid inputs.

---

## Features

1. **View Student List**: Displays the current list of students.
2. **Add New Student**: Allows adding a new student to the database.
3. **Search Student**: Searches for a specific student in the list.
4. **Remove Student**: Deletes a student from the list.
5. **Run Again Option**: Prompts the user to re-run the program or exit.

---

## How It Works

### Program Flow
- The program begins by displaying a welcome message and menu options.
- Users can select an option (1-4) to perform the desired operation.
- Upon completion of the selected operation, the program prompts the user to either run it again or exit.
- The program includes validation to handle invalid inputs and duplicate entries.

### Menu Options
- **Enter 1**: View the list of students.
- **Enter 2**: Add a new student to the list.
- **Enter 3**: Search for a student by name.
- **Enter 4**: Remove a student by name.

---

## Prerequisites

- **Python 3.x**: Ensure you have Python 3.x installed on your system.
- **Platform Support**: The script works on both Windows and Linux/macOS. It uses `os.system` to clear the terminal screen based on the OS.

---

## Installation

1. Clone or download this repository to your local machine.
2. Save the script as `student_management.py`.

---

## How to Run the Script

1. Open a terminal or command prompt.
2. Navigate to the directory where the script is saved.
3. Run the script using the following command:

   ```bash
   python student_management.py
   ```

4. Follow the on-screen prompts to interact with the program.

---

## Example

### Adding a New Student:

```
------------------------------------------------------
|======================================================|
|======== Welcome To Student Management System ========|
|======================================================|
------------------------------------------------------

Enter 1 : To View Student's List 
Enter 2 : To Add New Student 
Enter 3 : To Search Student 
Enter 4 : To Remove Student 

Please Select An Above Option: 2

Enter New Student: John

=> New Student John Successfully Add
=> yugesh
=> kishor
=> gajen
=> Gopi
=> John
```

### Searching for a Student:

```
Please Select An Above Option: 3

Enter Student Name To Search: John

=> Record Found Of Student John
```

### Removing a Student:

```
Please Select An Above Option: 4

Enter Student Name To Remove: John

=> Student John Successfully Deleted
=> yugesh
=> kishor
=> gajen
=> Gopi
```

---

## Code Overview

### Global Variables
- `listStd`: Stores the list of student names.
- `bye`: Stores the goodbye message displayed upon exit.

### Functions
1. **manageStudent**: Main function that displays the menu and performs operations based on user input.
2. **runAgain**: Prompts the user to rerun the program or exit.

### Error Handling
- Handles invalid input (e.g., entering text instead of numbers).
- Prevents adding duplicate student names.

---

## Customization
You can modify the script to:
- Save the student list to a file.
- Add more functionality like updating a student record.
- Implement a graphical user interface (GUI) using libraries like Tkinter.

---

## Credits
- **Developed By**: code-projects.org
- **Modified and Improved By**: [Your Name]

---

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.
