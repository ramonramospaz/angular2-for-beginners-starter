# Angular 2 For Beginners Playground
A playground for Getting Started with Angular 2.

# Installation pre-requisites

The playground has minimal dependencies, but you still need node and npm installed on your machine. 
These are some tutorials to install node in different operating systems. 

*Make sure to install the latest version of Node 6*

- [Install Node and NPM on Windows](https://www.youtube.com/watch?v=8ODS6RM6x7g)
- [Install Node and NPM on Linux](https://www.youtube.com/watch?v=yUdHk-Dk_BY)
- [Install Node and NPM on Mac](https://www.youtube.com/watch?v=Imj8PgG3bZU)

# Installation Instructions

First clone or download as a Zip file using the green "Clone Or Download" button on the top right of the document.

Then on the command line go into the folder and do:

    npm install
    
This should take a couple of minutes. If you have node 6 this should go smoothly. 

# Starting the development server

To start the server, run the following command:

npm start

When you type de command, it will show you where are you going to find the web server running. It will be something like this:

** browser-sync config **
{ injectChanges: false,
  files: [ './**/*.{html,htm,css,js}' ],
  watchOptions: { ignored: 'node_modules' },
  server: { baseDir: './', middleware: [ [Function], [Function] ] } }
[BS] Access URLs:
 -----------------------------------
       Local: http://localhost:3000
    External: http://10.0.13.70:3000
 -----------------------------------
          UI: http://localhost:3001
 UI External: http://10.0.13.70:3001
 -----------------------------------

# Making changes

If you edit a Typescript file and refresh the browser, the changes will be applied.




