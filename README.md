# MyReads Project:
A boiler static template was provided by Udacity's FEND Nanodegree course as a means to add react js in order to change status of the code from static to interactive.

# Step One:
Run npm install in the command prompt to ensure that all dependencies are present.  

# Step Two:
Consequently, then run npm start to ensure that the localhost:3000 is running and shows all static parent/child components on both the first main page and search page.

# Received from Udacity:
```bash
├── CONTRIBUTING.md
├── README.md - This file.
├── SEARCH_TERMS.md # A short collection of available search terms for use with app to ensure that it is interactive.
├── package.json # npm package manager file. Modified with npm install.
├── public
│   ├── favicon.ico # React Icon
│   └── index.html # No modifications implemented in this file.
└── src
    ├── App.css # App styles customized with dark blue and light grey background.
    ├── App.js # Root of app file that contained static html.
    ├── App.test.js # Used for testing. Provided with Create React App.
    ├── BooksAPI.js # A JavaScript API for the Udacity backend. 
    ├── icons # 
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── index.css # Global styles. No modifications implemented here.
    └── index.js # Browser Router information imported here from browser-react-dom.
```

Original static code was distributed into separate JS component files of FirstPage.JS, SearchPage.JS and Book.JS to ensure organization and that all statements were provided to change the app into a working instrument.

## Backend Server
Provided by Udacity in form of file named `BooksAPI.js` for implementation of all backend operations.

* [`getAll`](#getall)
* [`update`](#update)
* [`search`](#search)

### `getAll`

Method Signature:

```js
getAll()
```
* Returns a Promise which resolves to a JSON object containing a collection of book objects.
* This collection represents the books currently in the bookshelves in your app.

### `update`

Method Signature:

```js
update(book, shelf)
```

* book: `<Object>` containing at minimum an `id` attribute
* shelf: `<String>` contains one of ["wantToRead", "currentlyReading", "read"]  
* Returns a Promise which resolves to a JSON object containing the response data of the POST request

### `search`

Method Signature:

```js
search(query)
```

## Create React App

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). You can find more information on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Contributing

This repository is the starter code for _all_ Udacity students. Acknowledgement of much thanks for a thorough project walkthrough: Student Leader: Maeve from EMEA.  Her contribution brought all of the lessons together cohesively.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
