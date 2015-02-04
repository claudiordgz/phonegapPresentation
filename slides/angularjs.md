###  AngularJS

    app/
    ----- shared/   // acts as reusable components or partials of our site
    ---------- sidebar/
    --------------- sidebarDirective.js
    --------------- sidebarView.html
    ---------- article/
    --------------- articleDirective.js
    --------------- articleView.html
    ----- components/   // each component is treated as a mini Angular app
    ---------- home/
    --------------- homeController.js
    --------------- homeService.js
    --------------- homeView.html
    ----- app.module.js
    ----- app.routes.js
    
<br>

    assets/
    ----- img/      // Images and icons for your app
    ----- css/      // All styles and style related files (SCSS or LESS files)
    ----- js/       // Other JS files for your app
    ----- libs/     // Third-party libraries
    index.html