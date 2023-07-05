# LibraManage(Library Management System)

The Library Management System is a console-based application implemented in C++. It allows students and librarians to perform various operations related to library management, such as viewing the book list, searching for books, modifying book details, issuing books, and more.

## Features

- **Student Functionality:**
  - View the list of available books.
  - Search for books by name or ID.
  - Issue books from the library.

- **Librarian Functionality:**
  - Modify book details (name, author, quantity, etc.).
  - Add new books to the library.
  - Delete books from the library.
  - View the list of books based on branch and availability.

## Getting Started

To run the Library Management System on your local machine, follow these steps:

1. Make sure you have a C++ compiler installed on your system.

2. Clone this repository to your local machine or download the source code files.

3. Open the terminal or command prompt and navigate to the project directory.

4. Compile the source code files using the C++ compiler. For example:
   ```shell
   g++ main.cpp -o library
   ```

5. Run the executable file. For example:
   ```shell
   ./library
   ```

6. The program will start, and you will be prompted to enter your user type (student or librarian) and provide the necessary information to perform the desired operations.

## File Structure

The project directory contains the following files:

- `main.cpp`: The main source code file that implements the library management system.
- `Booksdata.txt`: A binary file that stores the book details.
- `README.md`: The readme file providing information about the project.

## Contributing

Contributions to the Library Management System project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
