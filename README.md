# get_next_line 📜

## Overview 📚
**get_next_line** is a project that involves creating a function to read a line from a file descriptor. This project, part of the **42cursus**, helps in understanding file operations, buffer management, and dynamic memory allocation in C. Through this project, I gained a deep understanding of how to handle input efficiently and manage memory dynamically.

## Key Skills and Concepts Learned 🛠️

### File Operations and Buffer Management 📂
- **File Descriptors**: Learned to work with file descriptors to read from files and standard input.
- **Buffer Management**: Implemented efficient buffer management to handle input of varying sizes without overflow or memory leaks.
- **Line Reading**: Developed a function to read a line from a file descriptor, handling different edge cases and ensuring robustness.

### Dynamic Memory Allocation 💾
- **Memory Allocation**: Gained expertise in using `malloc`, `free`, and `realloc` to manage dynamic memory.
- **Memory Safety**: Ensured memory safety by avoiding leaks and handling allocation failures gracefully.

### String Manipulation 📝
- **String Operations**: Implemented custom string operations to handle buffer contents, including concatenation, searching, and splitting.
- **Edge Case Handling**: Addressed various edge cases such as incomplete lines, empty files, and buffer boundaries.

### Code Organization and Best Practices 📏
- **Modular Code**: Organized code into separate modules for better readability and maintainability. Used helper functions to break down complex operations.
- **Norm Compliance**: Adhered to the 42 school's Norm, a set of coding standards that enforce good coding practices, ensuring consistency and readability across the project.

## Project Highlights 🌟

### get_next_line Function 🔄
- **Function Prototype**: Implemented the function `char *get_next_line(int fd);` to read a line from the given file descriptor.
- **Buffer Management**: Used a static buffer to handle input efficiently and minimize the number of system calls.
- **Memory Handling**: Ensured proper memory allocation and deallocation to avoid leaks and handle large inputs.

### Custom String Functions 📜
- **ft_strjoin_gnl**: Implemented a custom string join function to concatenate buffer contents dynamically.
- **ft_strchr_gnl**: Created a function to search for a character in a string, aiding in buffer management.
- **ft_strdup_gnl**: Developed a function to duplicate strings, ensuring proper memory allocation.

## Bonus Features 🎁
- **Multiple File Descriptors**: Extended the function to handle multiple file descriptors simultaneously, maintaining independent buffers for each.
- **Performance Optimization**: Optimized the function to handle large files and high-frequency input efficiently.

## Conclusion 🏁
Completing the **get_next_line** project was a significant milestone in my programming journey. It provided me with a solid foundation in file operations, buffer management, and dynamic memory allocation. The skills and knowledge gained through this project have prepared me to tackle more complex programming challenges and contribute effectively to any development team.

---

*This project is part of the 42cursus at [42 Network](https://www.42.fr/).*
