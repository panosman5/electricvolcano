-------------------------------------------------------------------------------------------------------
These are my ElectricVolcano notes. 
-------------------------------------------------------------------------------------------------------

## Build Setup

# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate


-------------------------------------------------------------------------------------------------------
PAGES
-------------------------------------------------------------------------------------------------------

You will find the site's pages, inside the pages folder. 
Currently these are the pages of the Project:

--- index.vue ---
This is the main page.

--- About.vue ---
This is the info page. It displays the info Stergios wants to display.

--- community.vue ---
This page includes the community links. To be updated according Stergios' 
comments. 

-------------------------------------------------------------------------------------------------------
COMPONENTS
-------------------------------------------------------------------------------------------------------

The components are the files we use again and again, without having to rewrite the same code over and 
over. 

--- Footer.vue ---
This component is about the footer. Make changes in this file, to change how the footer is displayed.

--- FrontPage.vue ---
This component is about the front page. Instead of working on the index.vue page (which is technically 
the same thing), i worked on the component, as a part of me getting used to Nuxt.

--- header.vue ---
This component is about the Navigation Bar at the top of the Webpage. It works in same fashion as footer.

-------------------------------------------------------------------------------------------------------
LAYOUTS
-------------------------------------------------------------------------------------------------------

This folder, includes the layouts.

--- default.vue ---
This default.vue file, controls how the structure of the pages will be. In case you want another layout,
you just create another file under the same folder and then import it in your page or component .vue file.

