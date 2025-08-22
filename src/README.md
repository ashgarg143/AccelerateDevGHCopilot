# Library App

## Description

Library App is a simple application designed to manage books, users, and borrowing activities in a library system. It provides core functionalities for cataloging, user management, and tracking book loans.

## Project Structure

- `src/`
    - `models/`
        - Book.cs
        - User.cs
        - Loan.cs
    - `services/`
        - LibraryService.cs
        - UserService.cs
        - LoanService.cs
    - `interfaces/`
        - IBookRepository.cs
        - IUserRepository.cs
        - ILoanRepository.cs
    - `controllers/`
        - BookController.cs
        - UserController.cs
        - LoanController.cs
    - Program.cs
    - Startup.cs
- `README.md`
- `LICENSE`

## Key Classes and Interfaces

- **Book**: Represents a book entity with properties like title, author, and ISBN.
- **User**: Represents a library user with details such as name and membership ID.
- **Loan**: Tracks the borrowing status of books by users.
- **LibraryService**: Provides business logic for managing books and loans.
- **IBookRepository, IUserRepository, ILoanRepository**: Interfaces for data access operations.
- **BookController, UserController, LoanController**: Handle API requests for respective entities.

## Usage

1. Clone the repository.
2. Restore dependencies and build the project.
3. Run the application using your preferred .NET runtime.
4. Access API endpoints to manage books, users, and loans.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.