Libft is a custom implementation of essential C standard library functions, developed as a project at 42 School. It serves as a foundational library for future C projects, reinforcing understanding of memory management, string manipulation, and basic data structures.



📚 Project Overview
The goal of Libft is to reimplement a selection of standard C functions from <ctype.h>, <stdlib.h>, and <string.h>, along with additional utility functions and linked list management tools, all coded from scratch without using any external libraries (except write, malloc, and free).



🛠️ Functions Implemented
Libft is divided into several parts:

Part 1: Standard C Functions
Functions that replicate the behavior of standard C functions:

ft_memset, ft_bzero, ft_memcpy, ft_memmove, ft_memchr, ft_memcmp

ft_strlen, ft_strlcpy, ft_strlcat, ft_strchr, ft_strrchr

ft_strncmp, ft_strnstr, ft_atoi, ft_strdup

ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint

ft_toupper, ft_tolower



Part 2: Additional Utility Functions
ft_calloc

ft_substr, ft_strjoin, ft_strtrim, ft_split

ft_itoa, ft_strmapi, ft_striteri

ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd



Bonus Part: Linked List Utilities
If included, this part provides functions for singly linked list manipulation:

ft_lstnew, ft_lstadd_front, ft_lstsize, ft_lstlast

ft_lstadd_back, ft_lstdelone, ft_lstclear, ft_lstiter, ft_lstmap



📁 Usage
To use this library in your own project:
git clone git@github.com:zmetreveli/LIBFT.git
cd libft
make



📄 License
This project is part of the 42 School curriculum and is intended for educational purposes only.

🧑‍💻 Author
Zurab Metreveli
42 Barcelona – Libft Project
