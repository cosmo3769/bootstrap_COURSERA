# bootstrap_COURSERA

## viewport

**npm init -y**

**npm install lite-server --save**

**npm install bootstrap jquery popper.js --save**

*All the development dependencies will be stored in package.json -->*

***"start": "npm run lite"***

***""lite": "lite-server"***

*code index.html --> The **viewport** meta tag ensures that the screen width is set to the device width and the content is rendered with this width in mind.*

**npm start**

*lite-server is a lightweight development web server with support for ***Single Page Apps (SPAs)*** *, serves a web app, opens it in the browser, refreshes when html or javascript change, injects CSS changes using sockets, and has a fallback page when a route is not found.*

## grid_system_part1

*The viewport meta tag ensures that the screen width is set to the device width and the content is rendered with this width in mind. This brings us to the second issue, designing the websites to be responsive to the size of the viewport. This is where the Bootstrap grid system comes to our aid. Bootstrap makes available four sizes, xs for extra small, sm for small, md for medium and lg for large screen sizes. We would like our website to have the content stacked on extra small devices, but become horizontal within each row for smaller devices and beyond. Towards this goal, we will make use of the classes .col-*, .col-sm-*, col-md-*, and .col-lg-* for defining the layouts for the various device sizes. We can specify how many columns each piece of content will occupy within a row, all adding up to 12 or a multiple thereof.*

**offset-1** *This shift one column away*

**order-sm-last && order-sm-first** *It orders the elements in container*

## grid_system_part2

