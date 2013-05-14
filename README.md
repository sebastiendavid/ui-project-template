This is a project template for front-end development.

- Served by NodeJS
- Dynamic server side Html generated by Express and Jade
- CSS generated by LESS
- Client side HTML/JavaScript powered by AngularJS
- Automated by Grunt

The goal of such project is to have a DEV MODE to facilitate the development, to generate the production files (JS & CSS minification), and to test them with the NodeJS server.  
After that, you can put your final static files where you want :)

###Requirements:

- [NodeJS](http://nodejs.org/download/)
- [Grunt](http://gruntjs.com/) ```npm install -g grunt-cli```

###Start the app

####First time you launch the app

```npm install```

####Start the app in Dev mode

```node start.js dev```  
URL: http://localhost:5000/index.html

####Build the production files

```grunt build```  
The files are generated in the folder ___dist___.

####Start the app with production files

```node start.js```  
URL: [http://localhost:5000/index.html](http://localhost:5000/index.html)  
To test the app without minification: [http://localhost:5000/index.html?beautify=true](http://localhost:5000/index.html?beautify=true)
