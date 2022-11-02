Installing webpack

npm -g i webpack@2.2.0

Using webpack through command line

webpack ./src/app.js ./dist/app.bundle.js
webpack ./src/app.js ./dist/app.bundle.js -p
webpack ./src/app.js ./dist/app.bundle.js -p --watch


Using webpack after creating the webpack config file and creating a new script

npm run dev