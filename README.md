# Admin Dashboard Application

This is a React application that provides a dashboard for displaying and managing a list of science books fetched from the Open Library API. The application includes features for searching, sorting, editing, and downloading book details, as well as a simple login interface.

## Features

1. **Login**
   - A simple login form with validation to access the dashboard.

2. **Search Books**
   - Allows users to search for books by the author's name.
   
3. **Sort Books**
   - Provides functionality to sort the list of books by various fields such as title, author name, ratings average, first publish year, subject, author birth date, and author top work.
   
4. **Edit Book Details**
   - Users can edit the details of each book directly in the dashboard.
   
5. **Pagination**
   - The book list is paginated for easy navigation, with controls to change the number of rows per page and navigate between pages.
   
6. **Download CSV**
   - Users can download the current list of books as a CSV file.
   


## Installation

To run this application locally, follow these steps:

1. **Clone the Repository**
   ```sh
   git clone https://github.com/vathsa1708/Nua_frontend.git
2. **Navigate to the Project Directory**

   ```sh
    cd admin-dashboard
    npm install
3. **Start the Development Server**

    ```sh
    npm start

## Usage
    
   1. **Login**
        - Username and Password Validation: Enter the correct username and password (e.g., username: admin, password: password) to access the dashboard.
   2.  **Search**
        - Use the search bar to find books by author name.
   3.  **Sort**
        - click on column headers to sort the book list by the corresponding field.
   4. **Edit**:
        - Click the edit icon next to a book to edit its details. Save changes by clicking the save button.
   5. **Pagination**
        - Use the pagination controls at the bottom of the table to navigate through pages of books.
   6. **Download CSV**
        - Click the "Download CSV" button to download the book list as a CSV file.

## Folder Structure
   - public/: Contains static assets and the index.html file.
   - src/: Contains the source code for the application.
   - components/: Contains the dashboard.js and Login.js components.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Deployment

The application is deployed on Vercel. You can access it [here](https://nua-frontend.vercel.app/).

## Contact
If you have any questions or feedback, please feel free to contact the repository owner.

Thank you for using the Admin Dashboard Application! We hope it serves your needs well.
