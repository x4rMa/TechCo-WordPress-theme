# WordPress custom theme
## designed for a technical company website

## 0.0.0 Planning a prototype
* The website will include a *Home* page, pages for *Products*, *Projects* and *Services*, an *About* page and a *Contact* page, as well as additional pages that will be built on the templates made for the basic pages.
* There will be a custom page design for the *Home* page, a plugin will be used for the *Contact* page and page-templates will be created for the rest of the pages.   

## 0.0.1 Set up the theme
* Add the required files *style.css* and *index.php*.
* Fill *style.css* in with the initial comments section.
* Create a basic *index.php* which echoes a main title with *get_the_title()* and contains the WordPress loop which calls *the_post()* and *the_content()*.

## 0.0.2 Header, Footer, Custom Front Page files
* Create the *header.php* and *footer.php* files and use the *wp_head()* and *wp_footer()* action hooks respectively.
* Create the *front-page.php* file wherein the custom page design for the *Home* page will be implemented later on.
* Use the *get_header()* and *get_footer()* functions in *front-page.php*.
