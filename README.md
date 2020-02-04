### React Tutorial

## Installing create-react-app

	npm install create-react-app -g

## Creating a new react app

	npx create-react-app my-app
	cd my-app
	npm start

### Working with React & Laravel

## Remove the default Vue scaffolding and replace it with React scaffolding 

	composer require laravel/ui --dev

	php artisan ui react

	// Generate login / registration scaffolding...
	php artisan ui react --auth

## Installing babel support while working with laravel

	npm install --save-dev babel-preset-stage-1 babel-preset-env babel-plugin-transform-class-properties babel-preset-react

## Create “.babelrc” file in your root folder, and add these following code:

	{
    "plugins": ["transform-class-properties"],
    "presets": [["env", {"modules": false}], "react"]
	}

## Now open your “webpack.mix.js” file and change “mix.react” to “mix.js”.

	npm run dev

