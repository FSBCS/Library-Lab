**Advanced Topics in Computer Science: End-of-Unit Project**

**Assignment Title:** Library Management System

**Objective:** Develop a Python-based library management system that handles books, patrons, and lending.

**Description:** 
Design a system for a local library to manage its books, patrons, and lending operations. This will assist the library staff in various tasks such as adding books, registering patrons, lending and returning books, and displaying book details. The system should also keep track of which patron has which book and if they've retained it beyond its due date.

---

**Requirements:**

1. **Multiple Classes**: Your system should at least have the following classes:
    - `Book`: To represent a single book.
    - `Patron`: To represent a library member.
    - `Lending`: To manage the lending details, such as due date.
    - `Library`: The main class that coordinates other classes to manage the complete system.

2. **Data Persistence**: Ensure that data remains even after the program is closed. Store data in either `.txt` or `.json` files.

3. **Error Handling**: Your program should be robust against common errors. For instance, handling situations where someone tries to borrow a book that's already checked out.

4. **User Interface**: Implement a simple command-line interface for the staff to interact with the system.

---

**Functionality:**

1. **Book**:
    - Add a new book (Title, Author, ISBN, Total Copies).
    - Remove a book using its ISBN.
    - View all books.
    - Search a book by title, author, or ISBN.

2. **Patron**:
    - Register a new patron (Name, ID, Address).
    - Remove a patron using ID.
    - View all patrons.

3. **Lending**:
    - Lend a book to a patron using the book's ISBN and patron's ID. Assign a due date (2 weeks from the lending date).
    - Return a book.
    - View all currently lent out books.
    - Highlight books that are overdue.

4. **Library**:
    - View the total number of books in the library.
    - View the total number of patrons.
    - View the total number of currently lent out books.

5. **Outputting and Displaying Multiple Records**:
    - Allow export of book, patron, or lending records as `.csv` or `.json` files.
    - Implement an option to view the aforementioned records in a tabulated format using the pandas package.

---

**Submission:** 
- Upload your project to a public GitHub repository.
- Submit the repository link on the provided Assignment Submission Platform.

---

Good luck with your project, and remember to collaborate effectively, share ideas, and enjoy the coding process!
