#Helper Marketplace

This is a starter template for the Help 4 Good application.

##App structure

* All Bootstrap components are compiled via Grunt to /dist
* All app-specific components live in /app

```
app/
├── img/
├── less/
├── js/
└── index.html
dist/
├── less/
├── js/
└── fonts/
```

#Build system

##To install, follow these steps:

* Install node.js
* Verify install by opening a terminal and typing `node -v`
* [Download the package](https://github.com/healthgovau/helper-marketplace/archive/master.zip) or clone the repo `git clone https://github.com/healthgovau/helper-marketplace.git` to a local folder of your choice
* Open a terminal at the local folder and run `npm install`

##To compile the app during development:

* Open a terminal at the root of the local folder and run:
  * `grunt dist` to compile JS, SCSS and fonts to /dist; or
  * `grunt watch` to compile SCSS only on change
* Open /index.html in the root