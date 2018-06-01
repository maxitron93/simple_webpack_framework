# Context
I made this simple framework so I wouldn't have to configure a webpack.config.js file everytime I want to create a simple one-page app. I can just download this repo and it's all setup. It enables the creation of a simple web app with:
- one HTML file
- multiple CSS files (by creating `.css` fils in `/src/css` and requiring them in `/src/js/index.js`)
- multiple JS files (by creating `.js` files in `/src/js`)

This framework comes with three commands:
- `npm run start`: starts a server that automatically reloads when changes are made in the `/src` directory.
- `npm run build`: compiles the files in the `/src` directory in production mode into files in the `/dist` folder
- `npm run dev`: compiles the files in the `/src` directory in development mode into files in the `/dist` folder




## How to use this framework
1. Clone this repo
2. cd into the directory and run `npm install`. This will install `webpack`, `webpack-cli`, `webpack-dev-server`, `html-webpack-plugin`, `css-loader`, `style-loader`
3. All setup! Work in the `/src` directory when developing the app, and run `npm run build` to compile the development code into production code in the `/dist` folder.

## More to come...
This framework currently doesn't provide a streamlined way to add additional HTML files or resources such as images or documents. I will add this functionality as I need it.