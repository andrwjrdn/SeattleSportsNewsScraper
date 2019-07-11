# Seattle Sports News Scraper

This app allows users to view Seattle Times news articles, save their favorites onto another page, and comment on their favorites. Each article displayed includes a headline which is also a link to the source article and a description that includes the date of publish. There is a 'remove' button next to each article on the saved articles page. The app uses Node/Express for the server and routing, MongoDB/Mongoose for the database and models, Handlebars for the layout and views, & Cheerio/Request for scraping.

[Live Demo]( https://multicultural-loon-31874.herokuapp.com/articles)

## Getting Started

1. Install dependencies 
2. In your CLI, enter **mongod**
3. In a new CLI window, go to root of directory and enter **node server.js**
4. In browser, navigate to **http://localhost:3000**

### Dependencies

You will need to npm install the following node modules:

1. express
2. express-handlebars
3. mongoose
4. body-parser
5. cheerio
6. request

Since I have included a package.json file, you do not need to install dependencies by name. Simply run the following in the root of your directory:

```
npm install
```


## Screenshots

