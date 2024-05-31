# NKOMIL364_BCL2401_BCL2401-D2_NkosinathiMilanzi__DJS04 
DJS04 Project Brief: Book Connect - Web Components
Building upon my "Book Connect" project in DJS03, I will now dive into Web Components. This challenge will refine my skills in creating reusable, encapsulated, and interactive elements.Book Connect App

Overview: This is the JavaScript code for the Book Connect app, a web application that allows users to search and browse books by title, author, and genre. The app features a responsive design, theme customization, and pagination.

Components:

Search Bar: Allows users to search for books by title, author, and genre.
Book List: Displays a list of books that match the search criteria, with pagination.
Settings: Enables users to customize the app's theme.
Header: Contains navigation links to the search bar and settings.
Features:

Search Functionality: Filters books by title, author, and genre.
Pagination: Limits the number of books displayed per page, with a "Show More" button to load additional books.
Theme Customization: Allows users to select a preferred theme, which is applied to the app's UI.
Responsive Design: Adapts to different screen sizes and devices.
Code Organization:

data.js: Contains the app's data, including books, authors, genres, and pagination settings.
helper.js: Houses utility functions for rendering book previews, setting up genre and author options, and applying theme properties.
elements.js: Defines the HTML elements used in the app.
Initialization:

The app is initialized by calling the initialization() function, which:

Renders the initial book previews.
Sets up the genre and author options.
Displays the "Show More" button.
Applies the preferred theme.
Event Listeners:

The app uses event listeners to respond to user interactions, including:

Search form submission
Setting form submission
Clicking on the "Show More" button
Clicking on a list item
Dependencies:

data.js: Required for accessing the app's data.
helper.js: Required for using utility functions.
elements.js: Required for accessing HTML elements.