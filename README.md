# Data-Scrapper
=============

Nodejs Daemon which will Scrap the IMDB Movie Data, Creates CSV file and store it.


### Requirements

1. Node.js installed

### How to use it ?

1. Make sure you have node.js installed.
2. cd to the application root and do `npm install` which installs the dependencies
3. Do `node .` to start the daemon.
4. Check root directory to see the scrapped movie data pushed as csv file.


### Node package dependencies

1. cheerio - as html parser
2. express - for the dashboard app
3. jade - templating engine
4. mongodb - node driver for mongo
5. socket.io - for the realtime push
