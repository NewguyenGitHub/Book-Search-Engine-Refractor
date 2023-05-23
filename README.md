# Book-Search-Engine-Refractor

## URL


## Description

This project is a book search engine using MERN stack.
The project allows users to signup and/or login to save their books and to review their list of saved books.
The user can search for books.
The user can sign up and/or login to save books.
The user can review the saved book(s).
The user can delete any saved book(s).
The user can logout.

## Summary

```
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
```

## Installation

npm i -y
npm run start

## Usage

This is a book search engine that allows users to signup and/or login to save their books and to review their list of saved books.

![Book-Search-Engine-Main](assets/demo/Book-Search-Engine-Main.JPG)

![Book-Search-Engine-Signup](assets/demo/Book-Search-Engine-Signup.JPG)

![Book-Search-Engine-Login](assets/demo/Book-Search-Engine-Login.JPG)

![Book-Search-Engine-Search-Results](assets/demo/Book-Search-Engine-Search-Results.JPG)

![Book-Search-Engine-Search-Save-this-Book](assets/demo/Book-Search-Engine-Search-Save-this-Book.JPG)

![Book-Search-Engine-Book-Already-Saved](assets/demo/Book-Search-Engine-Book-Already-Saved.JPG)

![Book-Search-Engine-See-Your-Books](assets/demo/Book-Search-Engine-See-Your-Books.JPG)

![Book-Search-Engine-Main](assets/demo)


## Credits

N/A

## License

Please refer to the LICENSE in the repo.
