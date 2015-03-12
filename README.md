# bourbonplay

Bourbonplay is a OOP SCSS themable structure founded on top of Bourbon, Neat and Bitters libraries.

An application must have an instance of the core directory and optionally themes.

The application base app.scss 

    //Core CSS 
    @import "../core/vendors/vendors";
    @import "../core/css/mixins";


    //Variables
    @import "../core/css/variables";
    @import "../themes/theme_a/css/variables";  //Theme hook - optional


    //Specifics
    @import "../core/css/core";
    @import "../themes/theme_a/css/theme";  //Theme hook - optional


## Themes

Themes are packages capable to overwritte core variables, add new variables, mixins, layout, structure and skin specifics. 
