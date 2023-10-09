# Library Management System

This is a simple library management system implemented in Python using the Tkinter library for the graphical user interface and SQLite for database storage. The system allows you to manage a library's inventory, add new books, update book details, delete books, and change the availability status of books.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Make sure you have Python installed on your system.

2. Clone the repository or download the source code as a ZIP file.

3. Navigate to the project directory.

4. Install the required libraries if not already installed. You can use `pip` to install them:

   ```shell
   pip install tkinter
   
   pip install sqlite3
   ```

5. Run the `library_management_system.py` script to start the application:

   ```shell
   python library_management_system.py
   ```

## Features

- Add new books to the library inventory.
- Update book details (name, author, status, issuer card ID).
- Delete individual book records.
- Delete the entire inventory.
- Change the availability status of books.
- View and search the library inventory.
- Graphical user interface for easy interaction.

## Usage

1. **Adding a New Book**: 
   - Fill in the book details (Name, ID, Author, and Status) in the left frame.
   - Click the "Add new record" button to add the book to the library inventory.

2. **Updating Book Details**:
   - Select a book from the library inventory by clicking on it.
   - Click the "Update book details" button to modify book information.

3. **Deleting Book Records**:
   - Select a book from the library inventory by clicking on it.
   - Click the "Delete book record" button to remove the selected book.

4. **Deleting Entire Inventory**:
   - Click the "Delete full inventory" button to clear the entire inventory. This action cannot be undone.

5. **Changing Book Availability**:
   - Select a book from the library inventory by clicking on it.
   - Click the "Change Book Availability" button to change the availability status of the book.

6. **Viewing Library Inventory**:
   - The right bottom frame displays the library's inventory in a table format.
   - You can scroll through the inventory and view book details.

## Contributing

Contributions are welcome! If you would like to contribute to this project, feel free to open issues, submit pull requests, or provide feedback.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for personal or commercial purposes.
