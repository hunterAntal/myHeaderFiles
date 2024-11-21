# myHeaderFiles

Welcome to **myHeaderFiles**, a personal repository containing custom **C header files** for various **data structures**, **algorithms**, and other utility functions. This repository is designed to serve as a reusable library for coding projects, assignments, and general experimentation with C programming.

---

## Directory Structure
The repository is organized for easy navigation and scalability:

myHeaderFiles/
├── README.md          # Documentation for the repository
├── data_structures/   # Header files for various data structures
│   ├── LL.h           # Linked List implementation
│   ├── Stack.h        # Stack implementation (coming soon)
│   ├── Queue.h        # Queue implementation (coming soon)
├── algorithms/        # Header files for algorithms
│   ├── Sorting.h      # Sorting algorithms (e.g., Bubble Sort, Quick Sort) (coming soon)
│   ├── Searching.h    # Searching algorithms (e.g., Binary Search) (coming soon)
├── utils/             # Utility functions and helper headers
│   ├── MathUtils.h    # Math-related utilities (coming soon)
│   ├── StringUtils.h  # String manipulation utilities (coming soon)
└── tests/             # Example programs to test each header file
    ├── test_LL.c      # Test file for Linked List (LL.h)
    ├── test_Stack.c   # Test file for Stack (coming soon)
    ├── test_Sorting.c # Test file for Sorting algorithms (coming soon)

---

## Features
- Reusable Code: Header files for common data structures and algorithms in C.
- Modular Design: Each file is self-contained, making it easy to include only what you need.
- Test Programs: Example programs in the `tests/` folder to help verify correctness.
- Extensibility: Easily add new header files and expand the library.

---

## Usage
### Including a Header File
To use a header file in your C project:
1. Clone the repository:
   git clone https://github.com/<your-username>/myHeaderFiles.git
2. Include the desired header file in your C program:
   #include "path/to/header_file.h"
   For example:
   #include "data_structures/LL.h"

3. Compile your program along with the corresponding `.c` files if required:
   gcc your_program.c LL.c -o your_program

---

## Header Files
### data_structures/LL.h
- Purpose: Implements a simple singly linked list.
- Features:
  - Add elements to the end of the list.
  - Push elements to the beginning of the list.
  - Remove the first element (pop).
  - Print the list.
  - Free the entire list.

---

## Contributing
Feel free to fork this repository and submit pull requests for new header files, features, or bug fixes. Contributions are welcome! 

---

## Testing
All header files are accompanied by test programs in the `tests/` folder. Run the test programs to verify functionality:
gcc tests/test_LL.c LL.c -o test_LL
./test_LL

---

## Future Plans
- Expand the **data_structures** library with more structures like stacks, queues, trees, and hash tables.
- Add common **algorithms** for sorting, searching, and graph traversal.
- Include **utility functions** for mathematical operations, string manipulation, and file I/O.
- Write comprehensive documentation for each header file.

---

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.

---

## Acknowledgments
Special thanks to:
- The C programming community for inspiration and resources.
- You, for exploring this project and considering its use! 😊

---

Happy coding! 🚀

