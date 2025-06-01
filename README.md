# Library Management System - README

## Description
This is a simple Library Management System web application built with HTML, CSS (using Tailwind CSS), and JavaScript. The application allows users to:

- Add new books with details like title, author, publication date, number of pages, and read status
- View all added books in a grid layout
- Toggle the read status of books
- Remove books from the library

The interface features a modern design with a blurred background image and a clean modal form for adding new books.

## Features
- Responsive design that works on different screen sizes
- Interactive modal form for adding books
- Visual indicators for read/unread books (different background colors)
- Ability to toggle read status and remove books
- Form validation for required fields

## How to Use
1. Open the `library.html` file in a web browser
2. Click the "Add book" button to open the form
3. Fill in all the required book information
4. Submit the form to add the book to your library
5. Use the "Mark as Read/Unread" buttons to change status
6. Use the "Remove" buttons to delete books

## Technical Details
- Built with vanilla JavaScript (no additional frameworks)
- Uses Tailwind CSS for styling
- All data is stored in-memory (no persistent storage)
- Simple modal implementation without external libraries

## Future Improvements
- Add persistent storage using localStorage or a backend
- Implement search/filter functionality
- Add book cover images
- Include more book details (genre, ISBN, etc.)
- Improve mobile responsiveness

## License
This project is open-source and available for anyone to use or modify.
