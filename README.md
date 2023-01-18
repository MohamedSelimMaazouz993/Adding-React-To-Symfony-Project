# Adding-React-To-Symfony-Project

### 1) composer require symfony/webpack-encore-bundle & 
### 2) now we edit webpack.config.js File and  uncomment //.enableReactPreset() ( line 70 for me ) to .enableReactPreset()
### 3) npm install or yarn install ( if you use yarn in the place of npm )
### 4) yarn add @babel/preset-react@^7.0.0 --dev
### 5) we modify our app.js file react component ( default as any react project )
### 6) encore dev --watch ( it will recommands so react packages to install ) 
### 7) npm install --save react react-dom react-dom-router
### 8) npm install --save react
### 9) encore dev --watch (again) 
### 10) symfony serve-d ( in a second terminal ) 
### And now you are good to go :D Enjoy !
