# About Ravenous
Ravenous is a restuarant search directory:
- users search for an eatery by *term* and *location*
- users prioritise search by *best match*, *highest rated*, or *most reviewed*
- search results are displayed visually as cards, detailing each business's image, name, address, rating, number of reviews and food category
- responsive SPA web app

This project was built as part of Codecademy Pro's [Create a Front-End App with React](https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-ajax-requests-and-api-interactions/modules/bwa-ravenous-part-four/projects/interacting-with-yelp-api) skill path. Webdesign and assets belong to Codecademy.

## Technologies:
- React.js 
- Yelp API
- HTML, CSS, JavaScript
- Create React App
- cors-anywhere
- node.js & npm

### Warning regarding cors-anywhere
Please note that [cors-anywhere](https://cors-anywhere.herokuapp.com/corsdemo) is used as a temporary workaround to CORS related issues which occur when developing a front-end app without a backend. In a commercial environment a project would have a backend and not need this CORS workaround.

The limitation of cors-anywhere is that access to this service is temporary. It runs out. Which stops the API from working, until access is requested manually from [cors-anywhere](https://cors-anywhere.herokuapp.com/corsdemo). Access lasts maybe one or two days only. 

It is fine to use as a stop-gap in development, or for people like myself who are building sample projects to develop and practice skills rather than for serious use, however is not a long term solution.


### Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). You can learn more in the [Create React App documentation](https://create-react-app.dev/docs/getting-started).

## Using this project
To run this project:
* you will need a node environment 
* clone or fork this project
* install npm in the root of the project directory
* to run the app in development mode, in the project directory run <code>npm start</code> and open [http://localhost:3000](http://localhost:3000) to view it in the browser.   
