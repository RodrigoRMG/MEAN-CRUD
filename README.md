
### RUN

    ##
    - npm install
    - node app.js




## Directory Layout

    app.js              --> app config
    package.json        --> for npm
    public/             --> all of the files to be used in on the client side
      stylesheets/              --> css files
        style.css         --> stylesheet
      img/              --> image files
      js/               --> javascript files
        app.js          --> declare top-level app module
        controllers.js  --> application controllers
          angular/
            angular.js            --> the latest angular js
    routes/
      api.js            --> route for serving JSON
      index.js          --> route for serving HTML pages and partials
    views/
      index.jade        --> main page for app
      layout.jade       --> doctype, title, head boilerplate
      partials/         --> angular view partials (partial jade templates)
        addPost.jade
        deletePost.jade
        editPost.jade
        indexPost.jade
        readPost.jade


