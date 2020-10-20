## React Google Books Search

Is an application created using the MERN stack and allows us to search for books via the Google Books API. Search results are dynamically rendered in the UI and we have the option to save or delete books.

View the deployed application at: <b><a href="https://google-books-react-search.heroku.app.com/" target="_blank">https://google-books-react-search.heroku.app.com/</a></b>

 Technologies Used
 - React JS
 - MongoDB
 - Mongoose
 - Express JS
 - Node
 - Axios

 How it works

1. Users are first directed to the `Home` page where they can search for any book. Book information is retrived via the publicly available Google Books API.

2. Upon searching for a book, users will see a list of relevant results. They can click `save` to save the book to the `Saved` page. In the back end, the book is saved to the Mongo database.

3. Users can save as many books as they want. If they then go to the `Saved` page, they'll not only see books that have been saved by them, but also previous visitor's saved books (it's basically a shared space of saved books).

4. In either the `Home` or `Saved` pages, a user can click on the `View Book` button. This will redirect them to the Google Books store page where they can either purchase or read a preview of the book.

5. If a user wants to remove a saved book from the list, they may click the `Delete` button to remove the book from the page. In the back end, this deletes the document from the Mongo database.


![Google Books Search](https://user-images.githubusercontent.com/52802240/77485425-55f33b00-6dea-11ea-986c-17e9e4572261.gif)





