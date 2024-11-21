# get_next_line - 1337 Project

## Description
`get_next_line` is a project from the 1337 curriculum where you are tasked with implementing a function that reads a single line from a file descriptor. The goal is to create a function that can handle reading lines of varying lengths, while managing memory efficiently. This project helps you understand file handling, buffers, dynamic memory allocation, and efficient data processing.

The `get_next_line` function should:
- Read one line at a time from a given file descriptor.
- Handle different line lengths and multiple reads.
- Return a line as a string (excluding the newline character).
- Ensure no memory leaks occur by properly managing dynamic memory.

## Features
- **Efficient Memory Usage**: The function should handle dynamic memory allocation and avoid memory leaks.
- **Handling of Multiple File Descriptors**: It can handle reading from multiple files simultaneously by managing static variables for each file descriptor.
- **Edge Case Handling**: Properly handles edge cases like:
  - End of file (EOF).
  - Buffer overflow.
  - Files that don't end with a newline.
  - Empty lines.
  
## Installation

### Clone the Repository:
```bash
git clone [https://github.com/yourusername/get_next_line.git](https://github.com/haghouli/get_next_line.git)
cd get_next_line
make
