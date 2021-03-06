# New York Times Article Search

This is a React.js app that allows users to search for New York Times articles. 

Use the app @ https://damp-harbor-86629.herokuapp.com/

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development. I will assume that you already have [Node.js](https://nodejs.org/en/) and [MongoDB](https://www.mongodb.com/) installed locally. See deployment for notes on how to deploy the project on a live system.

1. Install dependencies
2. In your CLI, enter **mongod**
3. In a new CLI window, go to root of directory and enter **node server.js**
4. In a third CLI window, go to root and enter **yarn start**. This will start the webpack dev server.

Your browser should automatically open a new tab containing the app.

### Dependencies

You will need to yarn install the following node modules:

1. express
2. mongoose
3. body-parser
4. bluebird
5. axios
6. react
7. react-dom
8. react-router-dom
9. react-scripts

Since I have included two package.json files, you do not need to install dependencies by name. Simply run the following in the root of your directory *as well as* in the Client folder:

```
yarn install
```

## Deployment

Follow these instructions to deploy your app live on Heroku

Create a heroku app in your project directory
```
heroku create <projectName>
```

Deploy the app
```
yarn deploy
```

Now your project should be successfully deployed on heroku.
