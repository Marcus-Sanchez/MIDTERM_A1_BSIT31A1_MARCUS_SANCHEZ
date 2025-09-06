# MIDTERM_A1_BSIT31A1_Marcus_Sanchez
## Library Management System

**Student:** Marcus Sanchez  
**Course:** BSIT 31A1  
**Project:** Midterm Assignment A1  

### Overview
This is a comprehensive Library Management System built using ASP.NET Core MVC framework. The system allows users to manage books, authors, and borrowing activities in a digital library environment.

### Features
- ✅ **Add New Books**: Add books with title, ISBN, and author information
- ✅ **View Library Collection**: Browse all available books in the library
- ✅ **Author Management**: Manage author details including biographies
- ✅ **Book Borrowing System**: Track which books are borrowed and by whom
- ✅ **User Management**: Manage library users and their borrowed books
- ✅ **Responsive Design**: Built with Bootstrap for modern UI/UX

### Technology Stack
- **Framework**: ASP.NET Core MVC (.NET 8.0)
- **Language**: C#
- **Frontend**: HTML5, CSS3, Bootstrap 5
- **Architecture**: Model-View-Controller (MVC)
- **Database**: In-memory data storage (for demonstration)

### Project Structure
```
MIDTERM_A1_BSIT31A1_Marcus_Sanchez/
├── LibraryManagementSystem/
│   ├── Controllers/
│   │   ├── HomeController.cs
│   │   └── LibraryController.cs
│   ├── Models/
│   │   ├── Author.cs
│   │   ├── Book.cs
│   │   ├── Library.cs
│   │   ├── User.cs
│   │   └── ErrorViewModel.cs
│   ├── Views/
│   │   ├── Home/
│   │   ├── Library/
│   │   └── Shared/
│   ├── wwwroot/
│   └── Program.cs
├── LibraryManagementSystem.sln
└── README.md
```

### Key Classes
- **Author**: Represents book authors with ID, name, and biography
- **Book**: Represents library books with title, ISBN, author, and borrowing status
- **Library**: Represents the library with location and book collection
- **User**: Represents library users with borrowed book tracking
- **LibraryController**: Main controller handling library operations
- **LibraryViewModel**: View model for passing data to views

### How to Run
1. Make sure you have .NET 8.0 SDK installed
2. Navigate to the LibraryManagementSystem directory
3. Run `dotnet restore` to restore packages
4. Run `dotnet build` to build the project
5. Run `dotnet run` to start the application
6. Open your browser to `http://localhost:5081`

### Usage
1. **Home Page**: Welcome page with feature overview and navigation to library
2. **Library Page**: Main functionality page where you can:
   - Add new books using the form at the top
   - View all books in a table format
   - See book details including title, ISBN, author, and borrowing status

### Sample Data
The system comes pre-loaded with 10 sample books including:
- Harry Potter by J.K. Rowling
- 1984 by George Orwell
- The Hobbit by J.R.R. Tolkien
- To Kill a Mockingbird by Harper Lee
- And more classic literature

### Future Enhancements
- Database integration (SQL Server/MySQL)
- User authentication and authorization
- Advanced search and filtering
- Book return functionality
- Reporting and analytics
- RESTful API endpoints

### Author Information
**Marcus Sanchez**  
BSIT 31A1 Student  
Library Management System - Midterm Project

---
*This project demonstrates proficiency in ASP.NET Core MVC, C# programming, and modern web development practices.*
