# React Tutorial

## Installing create-react-app

	npm install create-react-app -g

## Creating a new react app

	npx create-react-app my-app
	cd my-app
	npm start

## Working with React & Laravel

### Remove the default Vue scaffolding and replace it with React scaffolding 

	composer require laravel/ui --dev

	php artisan ui react

	// Generate login / registration scaffolding...
	php artisan ui react --auth

### Installing babel class-properties support while working with laravel & react

	npm install --save-dev @babel/plugin-proposal-class-properties

### Create “.babelrc” file in your root folder, and add these following code:

	{
	  "plugins": ["@babel/plugin-proposal-class-properties"]
	}

