Webpack takes all of our assets and outputs them to a production-ready bundle

 - Bundles JavaScript files into one file, minimizing http requests
 - Process SASS/LESS files into CSS and only use them where needed
 - Convert JSX or ES2015 into Vanilla JavaScript so browsers can understand.

Loaders

 - Perform transformations
 - E.g. Babel loaders transforms ES2015 or JSX into vanilla JS
 - Many more loaders for other things too (SASS, LESS, etc.)

Using Babel Loader

 - Install babel-core and babel-loader via npm
 - Install any presets we will be using to perform transformations
 - Configure webpack.config file to tell webpack to use babel to transform our code.

CSS Loaders

  - Use CSS loaders to load in only the styles we need, into different parts of our application.
  - CSS becomes much more modular and easier to manage.
  - 2 different loaders - css-loader, style-loader.
  - CSS-loader, loads the CSS into our JS file.
  - Style-loader adds our css into the DOM.
