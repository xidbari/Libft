Libft - Custom C Library

📖 Overview
Libft is a custom C library that reimplements a subset of standard C functions, along with some additional utility functions. This project serves as a foundation for future C projects, providing efficient and well-tested functions for string manipulation, memory operations, linked lists, and more.

📦 Features
🔧 Standard Functions (from <string.h>, <ctype.h>, <stdlib.h>, etc.)
String Manipulation:
ft_strlen, ft_strdup, ft_strchr, ft_strjoin, ft_split, etc.

Memory Operations:
ft_memset, ft_memcpy, ft_memmove, ft_memcmp, etc.

Character Checks:
ft_isalpha, ft_isdigit, ft_toupper, ft_tolower, etc.

Conversion & Allocation:
ft_atoi, ft_itoa, ft_calloc, etc.

🚀 Bonus Functions (Linked List Utilities)
ft_lstnew – Creates a new linked list node.

ft_lstadd_front – Adds a node to the beginning of a list.

ft_lstsize – Counts the number of nodes in a list.

ft_lstlast – Returns the last node of a list.

ft_lstiter – Applies a function to each node.

ft_lstclear – Deletes and frees an entire list.

✨ Extra Helpers
ft_putchar_fd, ft_putstr_fd – Output functions.

ft_substr – Extracts a substring.

ft_strtrim – Trims characters from the start and end of a string.

🛠️ Installation
Clone the repository:

sh
git clone https://github.com/yourusername/libft.git
cd libft
Compile the library:

sh
make
(This generates libft.a, a static library.)

Use in your project:

sh
gcc your_program.c -L. -lft -o your_program
✅ Testing
Run make test to execute included tests (if you have any).

Consider using Unity or libft-unit-test for thorough testing.

📜 Documentation
For detailed function descriptions, check the libft.h header file or generate documentation using Doxygen:

sh
doxygen Doxyfile
🤝 Contributing
Contributions are welcome!

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Commit your changes (git commit -m "Add some feature").

Push to the branch (git push origin feature/your-feature).

Open a Pull Request.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

📧 Contact
Abdi Osman – @xidbari

Email –idbariosman@gmail.com

