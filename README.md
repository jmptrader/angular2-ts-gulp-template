# angular2-ts-gulp-template
Quick start template for Angular 2 with Type Script and Gulp

Development Environment Setup:

1) Install Node JS

2) Install following npm global dependencies
	npm install -g gulp@3.9.1
	npm install -g gulp-cli@1.2.2
	npm install -g typings@1.0.4
	npm install -g typescript@1.8.10
	npm install -g ts-node@0.7.3

	Note: Check global dependencies by command "npm -g -depth 0 ls"


3) Install project dependencies using command "npm install" from the project root directory.
	node_modules and typings directories would be created once install is done

4) Build the project by following commands
	npm run clean & npm run build

5) Run the server by command "npm start"

Script created in Package.JSON

	clean - removes build directory

	compile - TypeScript compilation (with sourcemaps)

	build - build the project
	
	start - runs lite server which uses configuration from bs-config.json



http://blog.codeleak.pl/2016/03/quickstart-angular2-with-typescript-and.html