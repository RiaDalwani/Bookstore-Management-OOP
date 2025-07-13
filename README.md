# 📚 Bookstore Management System

This is a Java-based console application that simulates a simple bookstore system. It supports managing regular and special edition books with features like adding, listing, removing, and searching for books.

---

## 🚀 Features

- Add new books (regular or special edition)
- View all available books
- Search books by ISBN
- Remove books by ISBN
- Organize books by section
- Handle limited edition attributes for special books

---

## 🧱 Classes Used

### 1. `Book`
Represents a standard book.
- Attributes: `title`, `author`, `isbn`, `price`, `section`
- Method: `displayBook()`

### 2. `SpecialEditionBook` (inherits `Book`)
Represents a special edition book.
- Additional Attributes: `limitedEdition`, `extraContent`

### 3. `BookStore`
- Stores and manages an array of books
- Methods: `addBook()`, `removeBook()`, `searchBookByISBN()`, `displayAllBooks()`

### 4. `BookStoreManagement`
- Contains the `main()` method
- Provides the menu and user interaction logic

---

## 🛠️ How to Compile and Run

1. Navigate to the project directory:
   ```bash
   cd JavaProject/JavaProject/src
