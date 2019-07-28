### Html Development Environment with Bulma/Sass/Fontawesome 
Everything is preset for basic frontend development with Bulma. What you should do is
to run sass in bulma directory with the command: 

    sass --watch bulma.sass:bulma.css

This will update the **bulma.css** for any change in _**bulma.sass**_ 

Relative links to folders are also included in index.html for bulma.css and fontawesome.
I use (and love) **Vim** with **Bracey** plugin which render any change in html live. So i advise the same :)

NOTE: If you face the trouble of describing the root(working) directory in vim for bracey to reach the resources to show the pages for good, just type in vim your **pwd** as follows:

    :cd project-root

Happy coding
