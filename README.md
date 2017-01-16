# webpack-js
webpack sample tutorial

#How is webpack different?
* Code Splitting
* Loaders
* Clever parsing
* Plugin system
 

# install webpack 
npm install webpack -g
npm install --save-dev style-loader css-loader  # for !style css! 
but we will be binding loaders  --module-bind 'css=style!css'

# create the bundle
webpack ./entry.js bundle.js


