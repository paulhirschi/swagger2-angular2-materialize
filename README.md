Swagger 2 Angular 2 MaterializeCSS
==========

# Presentation
Swagger 2 UI made with Angular 2 and MaterializeCSS

# Demo
Feel free to try it here: [Swagger 2 UI Demo](http://linkia-demo.redfroggy.fr/swagger2)

# Features
- Responsive application
- Toolbar menu
- Api list
- Api detail
- Api execution
- Possibility to switch between request types (Accept header): for now only application/json and application/xml are supported
- Possibility to switch between response types (Content-Type header): for now only application/json and application/xml are supported
- Dynamic url construction when specifying parameters
- Responses messages listed in table
- Detailed model and sub models information: fields name, types, etc...
- Charts displaying requests time
- Possibility to compare statistics from one api to another

# Screenshots
![image](http://i.imgur.com/mppox2Y.png?1)
![image](http://i.imgur.com/pbkEvaT.png?1)
![image](http://i.imgur.com/xQ4nnKj.png?1)
![image](http://i.imgur.com/n3KcvFI.png?1)
![image](http://i.imgur.com/OBZHvqK.png?1) 

# Stack
- [Angular 2](https://angular.io)
- [MaterializeCSS](http://materializecss.com)
- Webpack
- Karma
- Jasmine
- PhantomJS

# Project Structure

```
- src: Sources folder
    -- app: Application files (TypeScript)
		-- boot.ts: Angular2 entry point
		-- app.component.ts: Booststrap component
		-- app.html: Bootsrap html
		-- directives: Angular 2 directives
		-- services: Angular 2 services
		-- model: Swagger api typescript definition
		-- components: Main components
		-- pipes: Angular2 @Pipe components
		-- utils: Utility classes
    -- assets: Assets folder
	   -- icons
	   -- styles
- typings: TypeScript interfaces for libraries
- node_modules (not in git repository): NPM dependencies
- karma.conf.js: Karma configuration file for unit tests (not yet)
- webpack.test.config.js: Build configuration file used for unit tests (not yet)
- webpack.config.js: Build configuration file
- tsconfig.json: TypeScript configuration file
- tslint.json: TSLint configuration file
- typings.json: Typings configuration file
- package.json: For managing npm dependencies and running scripts
- bs-config.json: Liter server configuration file
- dist: production folder
```


# Installation
Install the node dependencies:
```bash
$ npm install
```

# Execution
To start the server:
```bash
$ npm run start
```
To build the project:
```bash
$ npm run build
```