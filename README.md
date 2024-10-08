# Library Management System Application

![Project Front Page](path_to_your_front_page_image.jpg)

**Course**: CSE-310 (Operating System Lab)  
**Institution**: Green University of Bangladesh  
**Semester**: Spring 2024  
**Author**: MD Dulal Hossain (ID: 213902116)  
**Submission Date**: 05-06-2024  
**Instructor**: MD Solaiman Mia  

---

## Project Overview

[![Project Video Overview](path_to_thumbnail_image.jpg)](https://www.youtube.com/watch?v=your_video_link "Watch the video overview")

This **Library Management System** is a Bash-based script that allows users to manage book records through a command-line interface. Users can perform tasks like adding, finding, editing, removing, and viewing books. The system offers an easy-to-use interface with error handling and confirmation prompts, making it suitable for small library collections.

---

## Table of Contents
1. [Motivation](#motivation)
2. [Problem Definition](#problem-definition)
3. [Design Goals and Objectives](#design-goals-and-objectives)
4. [Applications](#applications)
5. [Project Details](#project-details)
6. [Implementation Workflow](#implementation-workflow)
7. [Tools and Libraries](#tools-and-libraries)
8. [Performance Evaluation](#performance-evaluation)
9. [Conclusion](#conclusion)
10. [Future Work](#future-work)

---

## Motivation

The project was motivated by the need for a simple, **command-line-based** solution to manage book records efficiently. It was designed to provide core functionalities like adding, searching, editing, and removing book entries while incorporating confirmation prompts and error handling to improve user experience.

---

## Problem Definition

The primary problem this project solves is the need for a basic **Library Management System** (LMS) that allows users to manage book records through a command-line interface. Users can perform operations like adding, finding, editing, removing, and viewing books while maintaining ease of use and reliability.

---

## Design Goals and Objectives

The design objectives for this system include:
- **Efficient Record Management**: Allow users to add, find, edit, and remove book entries seamlessly.
- **User-Friendly Interface**: Offer a menu-driven command-line interface for easy navigation.
- **Data Integrity**: Ensure data consistency through confirmation prompts and error handling.
- **Scalability**: Provide functionality that can be scaled for small libraries or individual users.

---

## Applications

This **Library Management System** can be applied in:
- **Small Libraries**: A simple system to maintain and manage library records.
- **Personal Use**: Individuals can use this system to organize their personal book collection.
- **Learning Tool**: This project provides a practical example of Bash scripting for beginners.

---

## Project Details

This project is built using **Bash scripting** to provide a command-line interface for managing library books. The system allows users to:
- **Add new books**: Input book details such as category, title, and author.
- **Search for books**: Find books by category or title.
- **Edit book records**: Modify existing book records.
- **Remove books**: Delete records from the system.
- **View all books**: Display a list of all stored books.

The project’s structure focuses on simplicity and ease of use, making it a functional tool for managing library records without the need for complex databases or interfaces.

---

## Implementation Workflow

1. **Main Menu**: Displays options for adding, finding, editing, removing, and viewing books.
2. **Add Books**: Prompts the user to enter book details (category, title, author) and confirms before saving.
3. **Find Books**: Searches the records for matching book titles or categories.
4. **Edit Books**: Allows users to update existing book records.
5. **Remove Books**: Deletes selected books from the system after confirmation.
6. **View Books**: Displays the list of all books stored in the system.
7. **Exit**: Ends the program.

---

## Tools and Libraries

- **Bash Scripting**: Core scripting language used to build the system.
- **Linux Environment**: The project runs on Unix-based operating systems.
- **Text Editors**: Tools like Vim or Nano were used for script development.
- **Unix Utilities**: Commands like `grep`, `wc`, `printf`, `rm`, and `clear` were used for text processing and file manipulation.
- **Trap Command**: Used for cleanup and handling interrupts (e.g., Ctrl+C).

---

## Performance Evaluation

### System Testing:
1. **Functionality**: Verified all features (adding, editing, finding, removing, viewing) work as expected.
2. **User Interface**: Tested for smooth user interaction through command-line prompts.
3. **Error Handling**: Ensured the system gracefully handles invalid input and provides user feedback.
4. **Security**: Basic checks for unauthorized changes to the system were tested.

### System Requirements:
- **RAM**: 16GB
- **Storage**: 512 GB SSD and 1TB HDD
- **Processor**: Intel Core i5 10th generation

---

## Conclusion

This **Library Management System** provides a simple yet efficient solution for managing book records through a command-line interface. With functionalities like adding, finding, editing, removing, and viewing books, the system enhances the user experience with clear prompts and error handling. It is a reliable tool for small libraries or personal use.

---

## Future Work

Enhancements for future versions of the project include:
1. **Graphical User Interface (GUI)**: Adding a GUI would make the system more accessible to users unfamiliar with command-line tools.
2. **Multi-User Support**: Allow concurrent access for multiple users to make the system scalable.
3. **Advanced Search**: Add more sophisticated search options for finding books.
4. **Data Validation**: Improve data validation mechanisms to prevent incorrect entries.
5. **Integration with External Systems**: Enable synchronization with other library systems or online catalogs.

---

## References

1. [Javatpoint Bash Tutorial](https://www.javatpoint.com/shell-scripting-tutorial)
2. [LearnShell.org](https://www.learnshell.org/)
3. [Udemy Shell Scripting Course](https://www.udemy.com/topic/shell-scripting/)
4. [TutorialsPoint Shell Scripting](https://www.tutorialspoint.com/unix/shell-scripting.htm)
5. [FreeCodeCamp Bash Scripting](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/)
