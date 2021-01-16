[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Badge for GitHub repo top language](https://img.shields.io/github/languages/top/hjlogique/Google-Books-React-Search?style=flat&logo=appveyor) ![Badge for GitHub last commit](https://img.shields.io/github/last-commit/hjlogique/Google-Books-React-Search?style=flat&logo=appveyor)
  
# Google-Books-React-Search

  ## Description 

  This React-based app allows users search for books via the Google Books API, and render them in a list. Users have the option to "View" the found books, bringing them to the books on Google Books, or "Save" books of their interest to a list, to be reviewed or purchased later. 
  
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [Questions](#questions)
  * [License](#license)
  
  ## Installation

  To run this app, you need first to install all the dependencies by running the `npm install` command in your integrated terminal at the root directory of the project. Once all the dependencies are installed, run the `npm start` command to start the `Express` server and the run the application. To build the application, run the `npm run build` command. To build this `MERN` application, `ReactJS`, `JavaScript`, `NodeJS`, `Express`and `MongoDB` are used. 
   
  ## Usage 
   
   Once the app is up and running, on the main or `Search` page, users can search for books by entering key words in the Search entry field in the `Book Search` section. The searched books are listed in the `Results` section in different rows. Each row includes some information about a book, like, title of the book, the author, the cover image and the description. There are two `View` and `Save` buttons in each row, which allow users to view the actual Google books site, and to save the book in a list in the `Search` page respectively. 
   
   On the `Search` page, in the `Saved Books` section, there is a list of all saved books displayed in different rows. Here the rows of books are identical to the ones in the `search` page, except they have a `Delete` button instead of the `Save` button. The `Delete` button removes the saved book from the list. 

   Once users save a book on the `Search` page, the saved book is removed from the list of searched books and added to the list of saved books in the `Save` page. This way, users are not allowed to resave the same book. The same way, once a book is deleted from the list of saved books, the deleted book will show up again in the list of searched books, if users choose to search for the same type of book.

   This app is deployed to `Heroku` and the book information are stored in a `Mongo` database.
   [Click here to go to the app on Heroku.](https://desolate-sierra-68513.herokuapp.com) Depending on the network speed, it might take a couple of seconds for the app to load.
   
   The following images display the `Search` and the `Save` pages:
   
  ![image 1](/screenshots/img1.png)

  ![image 1](/screenshots/img2.png)

  ## Contributing
  
  Please let me know if there are any ways to improve the logic, the code or the features of this application. Please also let me know about any found bugs or issues. I would really appreciate your contributions.
  
  ## Questions
  
  [Link to my GitHub profile](https://github.com/hjlogique)

  If you have any questions, please contact me via email:
  
  Email: hjlogique@yahoo.com
  
  ## License
  
  MIT License
