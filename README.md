# 🎓 Student Roster Program (C++)

This is a **C++ console application** that manages and displays a roster of students. It handles parsing student data, validates emails, calculates average completion times, filters students by degree program (specifically **Software**), and removes a student from the roster.

---

## 💡 Features

- Parse student data from raw input strings  
- Display student information in a formatted layout  
- Validate and list student email addresses  
- Calculate the average number of days to complete courses  
- Filter students in the **Software** degree program  
- Remove a student from the roster by their ID  

---

## 🛠️ Technologies Used

- **Language:** C++  
- **Compiler:** g++, MSVC, or Clang  
- **Standard:** C++11 or higher  
- **IDE (optional):** Visual Studio, Code::Blocks, VS Code  

---

## 🚀 Getting Started

### Prerequisites

- A working C++ compiler
- Command line or IDE to run the app

### Running the Program

1. Clone the repository:
    ```bash
    git clone https://github.com/Craig-Joiner/student-roster.git
    cd student-roster
    ```

2. Compile the program:
    ```bash
    g++ main.cpp Student.cpp Roster.cpp -o StudentRoster
    ```

3. Run the executable:
    ```bash
    ./StudentRoster
    ```

---

## 📁 Project Structure

/StudentRoster
├── main.cpp              // Contains your main() function and high-level logic
├── Student.h             // Student class declaration
├── Student.cpp           // Student class implementation
├── Roster.h              // Roster class declaration (manages the list of students)
├── Roster.cpp            // Roster class implementation
├── Degree.h              // Enum or constants for DegreeProgram (SOFTWARE, NETWORK, etc.)
├── README.md             // Your GitHub documentation file


## 📸 Sample Output

![image](https://github.com/user-attachments/assets/ddcc1934-6a5b-48ea-b447-d7e45a790de4)

