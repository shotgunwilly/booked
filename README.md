# BookEd

This is the beginning a project to create a document management system specifically for Open Text Books. The thought is to create a GitHub-esque document system which will make it easy to contribute, fork, and generate multiple electronic formats of books.

## Framework

This project will use the MEAN stack ([Mongodb](http://www.mongodb.org/), [Express](http://expressjs.com/), [Angular](http://angularjs.org/), [Node](http://nodejs.org/)) and was started with Brian Ford's [Angular-Express seed project](https://github.com/btford/angular-express-seed).

## Production

The application will be designed to deploy on [Heroku](http://www.heroku.com)

### Deployment Instructions

tbd

## Directory Layout
    
    app.js              --> app config
    package.json        --> for npm
    public/             --> all of the files to be used in on the client side
      css/              --> css files
        app.css         --> default stylesheet
      img/              --> image files
      js/               --> javascript files
        app.js          --> declare top-level app module
        controllers.js  --> application controllers
        directives.js   --> custom angular directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
        lib/            --> angular and 3rd party JavaScript libraries
          angular/
            angular.js            --> the latest angular js
            angular.min.js        --> the latest minified angular js
            angular-*.js          --> angular add-on modules
            version.txt           --> version number
    routes/
      api.js            --> route for serving JSON
      index.js          --> route for serving HTML pages and partials
    views/
      index.jade        --> main page for app
      layout.jade       --> doctype, title, head boilerplate
      partials/         --> angular view partials (partial jade templates)
        partial1.jade
        partial2.jade


## License
MIT
